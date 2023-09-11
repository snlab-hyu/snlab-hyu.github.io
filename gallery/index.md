---
title: Gallery
nav:
  order: 4
  tooltip: gallery
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Gallery

{% include section.html %}

.column {
  float: left;
  width: 50%;
}
{% include list.html data="posts" component="post-excerpt" %}
