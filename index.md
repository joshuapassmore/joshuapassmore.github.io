---
layout: home
title: Welcome
---

# Welcome to My Mathematics Website

Hello! I'm **Joshua Passmore**, a pure mathematics PhD student. This website is my space to share my passion for mathematics.

## Latest Posts

{% for post in site.posts limit:5 %}
  * [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
