---
layout: home
title: 首页
---

# 欢迎来到我的博客

这是我的技术博客，主要分享...

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y年%m月%d日" }}
{% endfor %}

[查看所有文章](/archive)