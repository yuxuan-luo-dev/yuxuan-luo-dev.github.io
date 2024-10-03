---
layout: default
title: Home
---

# Welcome to My Blog

Hello! I'm **[Your Name]**, and this is my personal blog where I share my thoughts, tutorials, and project updates.

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

