---
layout: page
title: "Blog"
permalink: /blog/
---

Occasional writing on:

- Neuroscience and brain–computer interfaces  
- Complex systems and emergent behavior  
- The future of AI and scientific tools  
- Random curiosities that refuse to leave my head  

{% if site.posts.size == 0 %}
_No posts yet — stay tuned._
{% else %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
{% endif %}
