---
layout: home
title: Welcome
---

![Joshua Passmore](photo.png)

Hello! I'm **Josh** (he/him), a pure mathematics PhD student based at the [University of the Western Cape](https://www.uwc.ac.za/) and the [African Institute for Mathematical Sciences (AIMS)](https://aims.ac.za/). For the most part, my research is based in pointfree topology (which I like to view as a lattice-based approach to general topology -- but also uses methods from category theory). I completed my Master's in 2025; you can find my thesis [here](https://uwcscholar.uwc.ac.za/items/74492698-1bbc-4858-b361-07f6ba42c2d3). 

## Latest Posts

{% for post in site.posts limit:5 %}
  * [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
