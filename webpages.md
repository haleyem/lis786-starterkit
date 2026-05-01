---
title: Articles & Webpages
layout: page
permalink: /webpages
nav-include: true
nav-order: 2
---
## Articles

{% include pressbooks_theory.md %}  

{% include big_three.md %}

{% for ideology in site.ideologies %}
<div id="ide">
<div class="content-left">
<h3><a href="/lis786-starterkit/{{ideology.permalink}}">{{ ideology.title }}</a></h3>
<p>{{ ideology.snip }}</p>
<p>{{ ideology.content }}</p>
</div>
{% if ideology.image %}
{% unless ideology.image == blank %}
<div class="img-right">
    <figure class="img-inner">
    <img src="{{ ideology.image }}">
    </figure>
</div>
{% endunless %}
{% endif %}
</div>
{% endfor %}

## General Resources

["Gender Equity Websites, Blogs, & Resources"](https://wcc.stanford.edu/community-resources-stanford/gender-equity-websites-blogs-resources) from Standford University

## Blogs

[Internation Feminist Journal of Politics Blog](https://www.ifjpglobal.org/blog)