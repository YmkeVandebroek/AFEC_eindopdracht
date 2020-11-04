---
title: 'Blog'
layout: 'layouts/blog.html'
pagination:
  data: collections.blog
  size: 2
permalink: 'blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'
paginationPrevText: 'Nieuwere posts'
paginationNextText: 'Oudere posts'
paginationAnchor: '#post-list'
css_extra: '/css/blog.css'
---

Hier geef ik een overzicht weer van projecten waar ik momenteel mee bezig ben.
