---
layout: default
---
<h1>参加するには</h1>
<div id="extended">
<p>
<a href='https://idobata.io/organizations/ruby-sapporo/rooms/talk/join_request/4d16ea48-e8bd-4f87-866e-6673fb9ea468'>Idobata</a>に入って適当に話しかけてください。
</p>
<p class="info"></p>
</div>
{% for post in site.categories.news limit:5 %}
<h1 class="entry-title"><a href="{{ post.url }}">{{ post.title }}</a></h1>
<div id="extended">
{{ post.content }}
</div>
<p class="info">Posted on <span class="date_posted">{{ post.date | date: "%Y-%m-%d" }}</span></p>
{% endfor %}
