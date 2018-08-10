---
layout: default
title: News
---

# Latest news

{% for post in site.posts limit:1 %}
  {% include news_item.html %}
{% endfor %}

