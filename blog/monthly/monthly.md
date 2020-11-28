---
title: Weekly Links
layout: default
date: 11/13/2020
permalink: /monthly/
---

{% include extras.html %}

Inspired by [Lawrence](https://www.wawrencelu.com/).

<ol>
{% assign sorted_pages = site.pages | sort: 'date' %}
  {% for p in sorted_pages %}
    {% if p.tag == "monthly" %}
    <a href="{{ p.url }}">
      <h2>{{ p.title }}</h2>
    </a>
    <h4>{{ p.date }}</h4>
    <p>{{ p.content }}</p>
    {% endif %}
  {% endfor %}
</ol>
