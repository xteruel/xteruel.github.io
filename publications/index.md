---
layout: default
title: publications
---
{% assign numPosts = site.categories["publications"] | size %}
{% for pub in site.categories["publications"] %}
   <span class="publication-item">
      <span class="id"> \[{{ numPosts }}\] </span>
      <span class="authors">{{ pub.people }}.</span>
      <a href="{{ pub.url | prepend: site.baseurl }}">
      <span class="title">{{ pub.title }}.</span>
      </a>
      <span class="info">{{ pub.info }}.</span>
      <span class="event">{{ pub.event | date: "%b, %Y" }}.</span>
      <span class="venue">{{ pub.venue }}.</span>
   </span>
   {% assign numPosts = numPosts | minus: 1 %}
{% endfor %}

