---
layout: default
title: Notebook
---

<section class="writing page-intro">
  <p>An intermittently updated collection of observations, notes, and essays.</p>
</section>


<ul class="posts">
  {% for post in site.categories.note %}
    {% if post.url %}
    <li class="post-summary">
        <header>
            <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        </header>
        <article>
          <p>{{ post.excerpt }}</p>
        </article>
        <footer>
          <p>
            {% for tag in post.tags %}
              {{ tag }}
            {% endfor %}
            <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date_to_string }}</time>
          </p>
        </footer>
    </li>
    {% endif %}
  {% endfor %}
</ul>
