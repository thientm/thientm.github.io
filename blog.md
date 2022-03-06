---
layout: default
title: blog
permalink: /blog/
---

<div class="row">
  {% for post in site.posts %}
  <div class="col-6 col-12-narrower">
    <section class="box special">
      <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
      <p>{{ post.excerpt }}</p>
      <ul class="actions special">
        <li><a href="{{ site.baseurl }}{{ post.url }}" class="button alt">Read More</a></li>
      </ul>
    </section>

  </div>
{% endfor %}
</div>
