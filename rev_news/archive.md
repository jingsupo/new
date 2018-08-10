---
layout: default
title: Git Rev News Archive
---

# Archive

Here you can see all the previous editions.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

