---
layout: default
title: Blog
---

[← Back to Home](./index.html)

# Blog

Welcome to my blog! Here I write about AI, MLOps, and my tech journey.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) - *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}
