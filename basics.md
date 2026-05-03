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
    <div class="container">
    <h3><a href="/lis786-starterkit{{ post.url }}">{{ vocab.title }}</a></h3>
    <p>{{ vocab.content }}</p>
    </div>
    {% endif %}
    {% endfor %}
</div>


## Questions  

### What is feminist theory?  
{% include pressbooks_theory.md %}  

{% comment %}
can i generate everything tagged a certain way here.... hmm... what is feminist theory? should all articles be in the articles collection?
{% endcomment %}



