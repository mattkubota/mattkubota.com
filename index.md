---
title: Matt Kubota
---

<main class="grid-1">
  <header class="item-1">
    <h1 class="font-size--xlarge">Matt Kubota is working on <a href="https://vocable.app" target="_blank" class="font-size--xlarge">Vocable AAC</a>.</h1>
  </header>
  <section class="item-2">yum yum yum</section>
  <section class="item-3">woof woof woof</section>
  <section class="item-4">yip yip yip</section>
  <footer class="item-5">
    <p>Coded by hand with <a href="https://jekyllrb.com/" target="_blank">Jekyll</a> and typeset with <a href="https://rsms.me/inter/" target="_blank">Inter</a>.</p>
    {% for item in site.data.navigation %}
      <a href="{{ item.link }}" {% if page.url == item.link %}class="current"{% endif %}>
        {{ item.name }}
      </a>
    {% endfor %}
  </footer>
</main>