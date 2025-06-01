---
layout: default
---

<a href="/">back</a>

<h2>{{ page.date | date: "%y-%m-%d" }}</h2>

<p>{{ page.salad }}</p>

<img class="saladimg" src="{{ site.baseurl }}/images/{{ page.image }}">

{{ content }}
