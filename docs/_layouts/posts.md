---
layout: default
---

<h1>saladposting.com</h1>
<p><i>eating salad every day in june</i></p>

<div class="postlinks">
{% for post in site.posts %}

<div class="postlink">
<a href="{{ post.url }}">{{ post.date | date: "%y-%m-%d" }}</a>

<a href="{{ post.url }}"><img src="{{ site.baseurl }}/images/{{ post.image }}"/></a>

</div>
{% endfor %}
</div>
