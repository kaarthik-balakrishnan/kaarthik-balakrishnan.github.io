---
layout: page
title: "Blog"
permalink: /blog/
---

Occasional writing on neuroscience, BCIs, physics, and the future.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
