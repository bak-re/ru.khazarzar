---
layout: default
---

<p><span class="marginnote" style="font-size:inherit;font-style:italic;">{{ page.citation }}</span><span style="color:gray;font-family:sans-serif;font-size:smaller;"><a href="{{ page.parturl }}" title="{{ page.partname }}">{{ page.partname }}</a> » {{ page.chaptername }}</span></p>
<h1>{{ page.title}}</h1>
<p class="subtitle">{{ page.date | date: "%B %-d, %Y" }}<span class="marginnote" ><img src="img/{{page.frontimage}}.jpg"/></span></p>


<p><a href="inf.htm" title="В оглавление"><strong>В оглавление</strong></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="{{ page.pagenext }}" title="Вперёд"><strong>Вперёд</strong></a></p>


{{ content }}

<p><a href="inf.htm" title="В оглавление"><strong>В оглавление</strong></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="{{ page.pagenext }}" title="Вперёд"><strong>Вперёд</strong></a></p>
