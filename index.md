---
layout: default
title: 首页
---

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

[查看所有文章](/archive.html)