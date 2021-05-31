---
layout: default
---
{% assign line=site.data.units | where: "pageid", page.pageid | first %}
<p><span class="marginnote" style="font-size:inherit;font-style:italic;line-height:1.4rem;">{{ line["citation"] }}</span><span style="color:gray;font-family:sans-serif;font-size:smaller;"><a href="{{ line["parturl"] }}" title="{{ line["partname"] }}">{{ line["partname"] }}</a> » {{ line["chaptername"] }}</span></p>
<h1>{{ line["title"]}}</h1>
<p class="subtitle">{{ page.date | date: "%B %-d, %Y" }}<span class="marginnote" >{% if line["frontimage"] %}<img src="img/{{line["frontimage"]}}.jpg"/>{% endif %}</span></p>


<p><a href="index" title="В оглавление"><strong>В оглавление</strong></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="{{ line["pagenext"] }}" title="Вперёд"><strong>Вперёд</strong></a></p>

{{ content }}

<p><a href="index" title="В оглавление"><strong>В оглавление</strong></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="{{ line["pagenext"] }}" title="Вперёд"><strong>Вперёд</strong></a></p>



