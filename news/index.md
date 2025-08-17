---
layout: default
title: News & Updates
nav_order: 8
---

# News & Updates

Stay up to date with our latest announcements and thought leadership.

{% for post in site.news %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}
