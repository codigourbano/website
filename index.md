---
layout: default
title: "Código Urbano"
---

<div class="home">
  <ul class="post-list-simple">
    {% for post in site.posts %}
      <li>
        <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</div>
