---
Title: Vocabulary
layout: post
permalink: /vocabulary
---

{% for post in site.tags.term %}
{{ post.title }}
{% endfor %}

<div markdown="1">
    {% for vocab in site.vocab %}
    <h3>{{ vocab.title }}</h3>
    <p>{{ vocab.content }}</p>
    {% endfor %}
</div>