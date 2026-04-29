---
Title: Movements
layout: post
permalink: /movements
---

{% for post in site.posts %}
{% for tag in post.tags %}
{% if tag == "movement" %}
{{ post.title }}
{% endif %}
{% endfor %}
{% endfor %}