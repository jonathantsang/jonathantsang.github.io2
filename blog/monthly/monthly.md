---
title: Weekly Links
layout: default
permalink: /monthly/
---

{% include extras.html %}

Inspired by [Lawrence](https://www.wawrencelu.com/) on [binarysearch.com](https://www.binarysearch.com).

<!-- sorting dates is bad so do this for now -->

<ol>
{% assign sorted_pages = site.pages | sort: 'order' | reverse %}
  {% for p in sorted_pages %}
    {% if p.tag == "monthly" %}
      <div>{% include collapsible-dropdown.html title=p.title content=p.content %}</div>
    {% endif %}
  {% endfor %}
</ol>
