---
layout: default
title: KKKK's Blog
---
<h1>{{ page.title }}</h1>

<p style="font-size:24px;">Writings:</p>
<ul>
　　{% for post in site.posts %}
　　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
　　{% endfor %}
</ul>