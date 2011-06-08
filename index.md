---
layout: default
---
{% for post in site.categories.news limit:5 %}
<h1 class="entry-title"><a href="{{ post.url }}">{{ post.title }}</a></h1>
<div id="extended">
{{ post.content }}
</div>
<p class="info">Posted on <span class="date_posted">{{ post.date | date: "%Y-%m-%d" }}</span></p>
{% endfor %}
