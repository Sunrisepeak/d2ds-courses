---
title: 公告
layout: default
nav_order: 2
---

# 课程公告

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}