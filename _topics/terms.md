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

<div markdown="1">
    {% for vocab in site.vocab %}
    <h3>{{ vocab.title }}</h3>
    <p>{{ vocab.content }}</p>
    {% endfor %}
</div>
