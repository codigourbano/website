---
layout: default
title: "Código Urbano"
---

<div class="home">
  <h1>Código Urbano</h1>
  <p class="subtitle">blog sobre dados abertos e tecnologias livres para as cidades</p>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <span class="post-date">{{ post.date | date: "%d/%m/%Y" }}</span>
        {% if post.categories %}
          <span class="post-categories">
            {% for category in post.categories %}
              {{ category }}
              {% unless forloop.last %} / {% endunless %}
            {% endfor %}
          </span>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
</div>
