---
layout: default
title: home
---

# Welcome to My Blog

Hello! I'm **Yuxuan Luo**, and this is my personal blog where I share my thoughts, tutorials, and project updates.

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}


