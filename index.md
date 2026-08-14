---
layout: default
description: About Joshua Passmore and his research in pointfree topology
---

<img src="{{ '/photo.webp' | relative_url }}" alt="Portrait of Joshua Passmore" width="450" height="675" class="profile-photo" decoding="async" fetchpriority="high">

Hello! I'm **Josh** (he/him), a pure mathematics PhD student based at the [University of the Western Cape](https://www.uwc.ac.za/) and the [African Institute for Mathematical Sciences (AIMS)](https://aims.ac.za/). My research is focused mainly on pointfree topology, which I like to view as a lattice-based approach to general topology that also draws on category theory. I completed my Master's in 2025; you can find my [thesis](https://uwcscholar.uwc.ac.za/items/74492698-1bbc-4858-b361-07f6ba42c2d3) online.

I work as a full-time teaching assistant at [AIMS South Africa](https://aims.ac.za/) for their MSc programme in Mathematical Sciences. I have been involved with courses ranging from Model Theory, taught by Dugald Macpherson, to Algebraic Systems Biology, taught by Matt Macauley. 

If you want to get in contact with me, my email address is: josh[at]aims[dot]ac[dot]za

## Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%-d %B %Y" }}
{% endfor %}

<!---## Publications

- *The foundations of locale theory* (MSc thesis, 2025)
- *Frames and ideals in pointfree topology* (Honours thesis, 2022) --->
