---
title: Blog Posts
layout: default
permalink: /blog/
---

{% include extras.html %}

<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <h2>Learning Blog Posts</h2>
      <p>Blog posts aimed towards undergrads with some useful information.</p>
      <ol>
        {% assign sorted_pages = site.pages | sort:"order" %}
        {% for p in sorted_pages %}
          {% if p.tag == "learning" and p.finished %}
          <li id="{{ p.order }}">
            <a href="{{ p.url }}">{{ p.title }}</a>
          </li>
          {% endif %}
        {% endfor %}
      </ol>
      </div>
    <div class="col-sm-4">
      <h2>Co-op Blog Posts</h2>
      <p>Blog posts focused mainly on the Waterloo co-op program and my co-op experiences.</p>
      <ol>
        {% assign sorted_pages = site.pages | sort:"order" %}
        {% for p in sorted_pages %}
          {% if p.tag == "co-op" and p.finished %}
            <li id="{{ p.order }}">
              <a href="{{ p.url }}">{{ p.title }}</a>
            </li>
          {% endif %}
        {% endfor %}
      </ol>
    </div>
    <div class="col-sm-4">
      <h2>General Blog Posts</h2>
      <p>Blog posts with non-academic topics.</p>
      <ol>
        {% assign sorted_pages = site.pages | sort:"order" %}
        {% for p in sorted_pages %}
          {% if p.tag == "general" and p.finished %}
          <li id="{{ p.order }}">
            <a href="{{ p.url }}">{{ p.title }}</a>
          </li>
          {% endif %}
        {% endfor %}
      </ol>
    </div>
    <div class="col-sm-4">
      <h2>Media Blog Posts</h2>
      <p>Blog posts talking about some form of media (movies, music, comics, video games, etc.)</p>
      <ol>
        {% assign sorted_pages = site.pages | sort:"order" %}
        {% for p in sorted_pages %}
          {% if p.tag == "media" and p.finished %}
          <li id="{{ p.order }}">
            <a href="{{ p.url }}">{{ p.title }}</a>
          </li>
          {% endif %}
        {% endfor %}
      </ol>
    </div>
    <div class="col-sm-4">
      <h2>Stories</h2>
      <p>Longer stories from my undergrad.</p>
      <ol>
        {% assign sorted_pages = site.pages | sort:"order" %}
        {% for p in sorted_pages %}
          {% if p.tag == "stories" and p.finished %}
          <li id="{{ p.order }}">
            <a href="{{ p.url }}">{{ p.title }}</a>
          </li>
          {% endif %}
        {% endfor %}
      </ol>
    </div>
  </div>
</div>

### Monthly Link Blog Posts

[Monthly Posts](/monthly)
