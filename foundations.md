---
title: Foundations
layout: page
permalink: /foundations
--- 

Mastering these skills will help ensure your essays have a strong foundation! 

Topics you'll find here include: 

- Thesis statements
- Topic sentences
- Annotated bibliography

{% for resource in site.resources %}
{% if resource.category == 'foundations' %}
<h3><a href="{{ resource.url }}">{{ resource.title }}</a></h3>
<p><img src="{{ resource.image }}" alt="{{ resource.alt }}"/></p>
<p>{{ resource.content }}</p>
<p>Category: {{ resource.category }}</p>
{% endif %}
{% endfor %}