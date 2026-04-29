---
title: Basic Feminist Concepts
layout: page
permalink: /basics
nav-include: true
nav-order: 3
---

INTRO

## Feminist Vocabulary

These terms are used across different feminist theories. The nuances of the terms will change, but the basic meaning as presented here will stay the same.  


<div>
    {% for vocab in site.vocab %}
    <h3>{{ vocab.title }}</h3>
    <p><img src="{{vocab.image}}"></p>
    <p>{{ vocab.content }}</p>
    <p>Part of {{ vocab.category }}</p>
    <p>{{ vocab.tags }}</p>
    {% endfor %}
</div>

<div>
{% for  %}

I want only foundational vocab on the vocab page; how?


# Resources

[text](https://opentext.wsu.edu/theoreticalmodelsforteachingandresearch/chapter/feminist-theory/)  