---
layout: default
title: <h4>KKKK's Blog<h4>
---
<h1>{{ page.title }}<h1>

<p style="font-size:36px;" align="center">about me</p>
<p style="font-size:30px;color:blue;">Writings(latestly):</p>
<ul style="font-size:22px;">
　　{% for post in site.posts %}
　　　　<li>{{ post.date | date_to_string }} &emsp;<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
　　{% endfor %}
</ul>

<p style="font-size:30px;color:blue;">Pics:</p>

<a href="https://sm.ms/image/ScnTpqQCoKe2LiM" target="_blank"><img src="https://i.loli.net/2019/08/31/ScnTpqQCoKe2LiM.jpg" height="400" width="800"></a>