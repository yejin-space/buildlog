---
layout: home
title: buildlog
subtitle: Quietly stacking little notes — shaping them into my own story.
---

{% for post in site.posts %}
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%Y-%m-%d" }}</p>
  <p>{{ post.excerpt }}</p>
  <hr />
{% endfor %}