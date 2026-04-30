---
title: Feminist Theories
layout: page
permalink: /theories
nav-include: true
---

{% for theory in site.theories %}
    <div class="container">
    <h4><b>{{ theory.title }}</b></h4>
    <img src="{{theory.image}}" alt="image-alt" style="width:100%">
    <p>{{ theory.content }}<p>
    </div>
{% endfor %}
