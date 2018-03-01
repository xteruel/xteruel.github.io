---
layout: default
title: talks
---
{% assign numPosts = site.categories["talks"] | size %}
{% for post in site.categories["talks"] %}
   <span class="publication-item">
      <span class="id"> \[{{ numPosts }}\] </span>
      <span class="title">{{ post.title }}.</span>
      <span class="event">{{ post.event | date: "%b, %Y" }}.</span>
      <span class="venue">{{ post.venue }}.</span>
   </span>
   {% assign numPosts = numPosts | minus: 1 %}
{% endfor %}
