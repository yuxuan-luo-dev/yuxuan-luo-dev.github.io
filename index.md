---
layout: default
title: Home
---

# Welcome to My Blog

Hello! I'm **[Your Name]**, and this is my personal blog where I share my thoughts, tutorials, and project updates.

## Navigation
- [About](about.md)
- [CV](cv.md)
- [Blog](blog.md)
- [Projects](projects.md)

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}


