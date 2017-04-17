---
layout: default
title: List of publications
kind: publications
---
{% for post in site.posts %}
   {% if post.kind == "publication" %}
   <span class="post-publication">
      <span class="authors">{{ post.authors }}.</span>
      <span class="title">{{ post.title }}.</span>
      <span class="info">{{ post.info }}.</span>
      <span class="venue">{{ post.venue }}.</span>
   </span>
   {% endif %}  
{% endfor %}



