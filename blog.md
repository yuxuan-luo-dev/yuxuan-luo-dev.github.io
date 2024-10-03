---
layout: default
title: Blog
---

# Blog

Here are my recent blog posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - *{{ post.date | date_to_long_string }}*
{% endfor %}
