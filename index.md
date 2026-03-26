---
layout: home
title: Anish Feroz
---

# Anish Feroz

Offensive Security Specialist

This blog contains research on:

- exploit development
- mobile security
- vulnerability research
- offensive security

---

## Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
