---
layout: collection
title: "Galería"
collection: camisetas
---

{% for item in site.camisetas %}
  <div class="gallery-item">
    <img src="{{ item.image }}" alt="{{ item.title }}">
    <h3>{{ item.title }}</h3>
    <p>{{ item.description }}</p>
  </div>
{% endfor %}
