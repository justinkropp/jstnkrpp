---
layout: default
title: Projects
---

<section class="work page-intro">
  <p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus.</p>
</section>

<section class="projects">
  {% for post in site.categories.project %}
    {% if post.url %}
          <article class="project-tldr">
          <!-- {% if post.featured-image %}{% include post-featured-image.html image=post.featured-image alt=post.featured-image-alt %}{% endif %} -->
          <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
          <p>{{ post.excerpt }}</p>
          </article>
    {% endif %}
  {% endfor %}
</section>
