---
layout: home
title: Welcome
---

# Welcome to My Mathematics Website

Hello! I'm **Josh**, a pure mathematics PhD student based at the University of the Western Cape and the African Institute for Mathematical Sciences (AIMS). My research is based in pointfree topology... 

## Latest Posts

{% for post in site.posts limit:5 %}
  * [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
