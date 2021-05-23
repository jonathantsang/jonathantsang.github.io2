---
layout: default_no_footer
---
<style>
div.img {
    border: 1px solid #ccc;
}

div.img:hover {
    border: 1px solid #777;
}

div.img img {
    width: 100%;
    height: auto;
}
</style>

<h1>{{ page.title }} Photos</h1>

<div class="container">
  <div class="row">
    {% for image in site.static_files %}
        {% if image.path contains page.tag %}
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="img"><a href="{{ site.baseurl }}{{ image.path }}"><img src="{{ site.baseurl }}{{ image.path }}" alt="image" /></a>
          </div>
        </div>
        {% endif %}
    {% endfor %}
    </div>
</div>
