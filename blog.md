---
layout: default
title: Blog
---

# This is my **Blog**

{% for post in site.posts %}
* _{{ post.date | date: "%-d %b %Y %R" }}_ - **<a href="{{ post.url }}"> {{ post.title }}</a>**
{% endfor %}

