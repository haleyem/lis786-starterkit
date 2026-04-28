---
title: Basic Feminist Concepts
layout: page
permalink: /basics
order: 3
---

## Feminist Vocabulary

These terms are used across different feminist theories. The nuances of the terms will change, but the basic meaning as presented here will stay the same.  

```
<div>
    {% for vocab in site.vocab %}
    <h3>{{ vocab.title }}</h3>
    <p><img src="{{vocab.image}}"></p>
    <p>{{ vocab.content }}</p>
    <p>Part of {{ vocab.category }}</p>
    {% endfor %}
</div>
```

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