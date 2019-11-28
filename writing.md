---
layout: page
title: Writing
---

<section class="page">
  <h2>Writing</h2>
  <p class="page-intro">Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, lacinia odio.</p>

  <ul class="post-index">
    {% for post in site.posts %}
      <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endfor %}
  </ul>

</section>
