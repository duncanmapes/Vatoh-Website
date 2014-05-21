---
layout: page
title: Services
permalink: /services/
---

This is the products and services page for Vatoh.com.  not sure that i like this...but it has some coolness to it.

Products:  Business VOIP solutions.

<ul>
{% for product in site.data.products %}
  <li>
    <a href="https://github.com/{{ product.name }}">
      {{ product.name }}
    </a>
    {{ product.desc }}
  </li>
{% endfor %}
</ul>
