---
layout: post
title: Note Template
excerpt: Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Donec ullamcorper nulla non metus auctor fringilla.
category: note
tags: template
published: false
---

<section class="grid  note-intro">
  <header>
    <h2>{{ page.title }}</h2>
    <time>{{ page.date | date_to_string }}</time>
  </header>
  <article>
    <p>Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor.</p>
    <p>Sed posuere consectetur est at lobortis. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas faucibus mollis interdum. Donec ullamcorper nulla non metus auctor fringilla. Maecenas sed diam eget risus varius blandit sit amet non magna. Aenean lacinia bibendum nulla sed consectetur.</p>
  </article>
  <footer>
    <p>
      {% for tag in post.tags %}
        {{ tag }}
      {% endfor %}
    </p>
  </footer>
</section>

<section class="grid note-image">
  <figure>
    <img src="/img/fpo.png">
    <figcaption>
      <h4>Fig. A</h4>
      <p>Morbi leo risus, porta ac consectetur ac, vestibulum at eros.</p>
    </figcaption>
  </figure>
</section>

<section class="grid note-words">
  <article>
    <p>Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor.</p>
    <p>Sed posuere consectetur est at lobortis. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas faucibus mollis interdum. Donec ullamcorper nulla non metus auctor fringilla. Maecenas sed diam eget risus varius blandit sit amet non magna. Aenean lacinia bibendum nulla sed consectetur.</p>
  </article>
</section>

<section class="grid note-image">
  <figure>
    <img src="/img/fpo.png">
    <figcaption>
      <h4>Fig. A</h4>
      <p>Morbi leo risus, porta ac consectetur ac, vestibulum at eros.</p>
    </figcaption>
  </figure>
</section>
