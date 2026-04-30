---
Title: Movements
layout: post
snip: Social, political and economic feminists movements with a specific goal in mind.
permalink: /movements
---

{% for post in site.posts %}
{% for tag in post.tags %}
{% if tag == "movement" %}
{{ post.title }}
{% endif %}
{% endfor %}
{% endfor %}