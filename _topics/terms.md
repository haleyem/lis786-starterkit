---
Title: Terms
layout: post
snip: Definitions of terminology. 
permalink: /terms
---

{% for post in site.posts %}
{% for tags in post.tags %}
{% if tags == "term" %}
{{ post.title }}
{% endif %}
{% endfor %}
{% endfor %}

{{ site.tags.term }}
