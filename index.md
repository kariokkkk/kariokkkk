---
layout: default
title: <h4>KKKK's Blog<h4>
---
<h1>{{ page.title }}</h1>
<p style="font-size:50px;"align="center">about me</p>

<p style="font-size:36px;color:blue;">Writings(latestly):</p>
<ul style="font-size:25px;">
　　{% for post in site.posts %}
　　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">&emsp;{{ post.title }}</a></li>
　　{% endfor %}
</ul>

<a href="https://sm.ms/image/ScnTpqQCoKe2LiM" target="_blank"><img src="https://i.loli.net/2019/08/31/ScnTpqQCoKe2LiM.jpg" height="200" ></a>