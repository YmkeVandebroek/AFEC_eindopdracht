---
title: 'Werk'
layout: 'layouts/page.html'
css_extra: '/css/werk.css'
---

{% for item in collections.featuredWork %}
  <a href="{{ item.url }}">
    <h4>{{ item.data.title }}</h4>
    <img src="{{ item.data.image }}" alt="{{ item.data.summary }}"/>
  </a>
{% endfor %}
