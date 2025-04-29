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
<a href="{{ resource.url }}" class="resource-card">
<h3>{{ resource.title }}</h3>
<p><img src="{{ resource.image }}" alt="{{ resource.alt }}"/></p>
<p>{{ resource.content }}</p>
<p>Category: {{ resource.category }}</p>
</a>
{% endif %}
{% endfor %}
