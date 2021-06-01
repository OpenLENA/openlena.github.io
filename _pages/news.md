---
# title: "Posts by Year"
title: ""
permalink: /news/
layout: news
author_profile: true
---

<!-- {% for post in site.posts %}
  {% unless post.tags contains "question" %}
  <article class="index-page">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.content | strip_html | truncatewords: 50 }}
    {% if post.lastmod %}
      <span class="date">{{ post.lastmod | date: "%d-%m-%Y"  }}</span>
    {% else %}
      <span class="date">{{ post.date | date: "%d-%m-%Y"  }}</span>
    {% endif %}
  </article>
  {% endunless %}
{% endfor %} -->