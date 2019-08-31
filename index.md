---
layout: default
title: KKKK's Blog
---
<h2>{{ page.title }}</h2>
<p>Writings:</p>
<ul>
　　{% for post in site.posts %} <br>
　　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li><br>
　　{% endfor %}
</ul>