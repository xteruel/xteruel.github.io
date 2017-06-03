---
layout: default
categories: publications
title: List of publications
---
{% for post in site.categories["publications"] %}
   <span class="publication-item">
      <span class="authors">{{ post.people }}.</span>
      <span class="title">{{ post.title }}.</span>
      <span class="info">{{ post.info }}.</span>
      <span class="event">{{ post.event | date: "%b, %Y" }}.</span>
      <span class="venue">{{ post.venue }}.</span>
   </span>
{% endfor %}

