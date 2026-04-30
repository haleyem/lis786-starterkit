---
Title: Vocabulary
layout: post
permalink: /vocabulary
---

{% for post in site.posts %}
{% for tag in post.tags %}
{% if tag == "term" %}
{{ post.title }}
{% endif %}
{% endfor %}
{% endfor %}


{% for vocab in site.vocab %}
{{ vocab.title }}
{{ vocab.content }}
{% endfor %}

