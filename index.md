---
layout: default
title: <h3>KKKK's Blog<h3>
---
<h1>{{ page.title }}</h1>
<h1 style="font-size:50px;"align="center">about me<h1>

<p style="font-size:36px;">Writings:</p>
<ul style="font-size:25px;">
　　{% for post in site.posts %}
　　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
　　{% endfor %}
</ul>

<a href="https://sm.ms/image/ScnTpqQCoKe2LiM" target="_blank"><img src="https://i.loli.net/2019/08/31/ScnTpqQCoKe2LiM.jpg" ></a>