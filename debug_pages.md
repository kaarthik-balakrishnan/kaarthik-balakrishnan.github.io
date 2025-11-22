---
layout: none
permalink: /debug-pages/
---

<ul>
{% for p in site.pages %}
  <li>{{ p.path }} — url: {{ p.url }} — title: {{ p.title | default: 'NO_TITLE' }} — published: {{ p.published | default: 'true' }}</li>
{% endfor %}
</ul>
