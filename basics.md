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

I want only foundational vocab on the vocab page; how?

## Liberal Feminism

{% include short-lib.md %}  
[Click here for more information on liberal feminism.](/lib.md)

## Marxist Feminism

{% include short-marx.md %}
[Click here for more information on Marxist feminism.](/marx.md)

## Radical Feminism

{% include short-rad.md %}
[Click here for more information on radical feminism.](/rad.md)

## Womanism

{% include short-wom.md %}
Click here for more information on Womanism.



# Resources

[text](https://opentext.wsu.edu/theoreticalmodelsforteachingandresearch/chapter/feminist-theory/)  