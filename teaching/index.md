---
layout: default
categories: teaching
title: List of tutorials
---
{% for post in site.categories["teaching"] %}
   <span class="publication-item">
      <span class="title">{{ post.title }}.</span>
      <span class="event">{{ post.event | date: "%b, %Y" }}.</span>
      <span class="venue">{{ post.venue }}.</span>
   </span>
{% endfor %}

