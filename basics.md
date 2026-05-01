---
title: Basic Feminist Concepts
layout: page
permalink: /basics
nav-include: true
---

Simplified term defintions and background information, plus some introductional resources. 

## Feminist Vocabulary

These terms are used across different feminist theories. The nuances of the terms will change, but the basic meaning as presented here will stay the same.  


<div>
    {% for vocab in site.vocab %}
    {% if vocab.category contains "foundations" %}
    <h3>{{ vocab.title }}</h3>
    <p><img src="{{vocab.image}}"></p>
    <p>{{ vocab.content }}</p>
    {% endfor %}
</div>

## Feminist Ideologies

Intro to various feminist ideologies. Coming soon...  

## More Resources...  

### What is feminist theory?  
{% include pressbooks_theory.md %}  



