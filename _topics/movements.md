---
Title: Movements
layout: post
snip: Social, political and economic feminists movements with a specific goal in mind.
image: /lis786-starterkit/images/votes.png
permalink: /movements
---

{% for post in site.posts %}
{% for tags in post.tags %}
{% if tags == "movement" %}
{{ post.title }}
{% endif %}
{% endfor %}
{% endfor %}
{{ page.image }}