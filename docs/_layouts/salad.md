---
layout: default
---

<a href="/">back</a>

<h2>{{ page.date | date: "%Y-%m-%d" }}</h2>

<p>{{ page.salad }}</p>

{{ content }}

{% if page.image %}
<img class="saladimg" src="{{ site.baseurl }}/images/{{ page.image }}">
{% endif %}
