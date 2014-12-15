---
layout: alt-page2
title: F.A.Q.
excerpt:
---

<ul class="post-list">
{% for post in site.categories.faq %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></article></li>
{% endfor %}
</ul>
