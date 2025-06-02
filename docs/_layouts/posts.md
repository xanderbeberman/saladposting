---
layout: default
---

<h1>eating salad every day in june</h1>

<div class="postlinks">
{% for post in site.posts %}

<div class="postlink">
<a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }}</a>

<a href="{{ post.url }}"><img src="{{ site.baseurl }}/images/{{ post.image }}"/></a>

</div>
{% endfor %}
</div>
