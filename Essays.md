---
title: Essays
layout: page
permalink: /essays
---
# Essays 

Review different essay and assignment types, including: 

- Academic journaling 
- Rhetorical analysis 

{% for resource in site.resources %}
{% if resource.category == 'Essays' %}
<h3>{{ resource.title }}</h3>
<p><img src="{{ resource.image }}" alt="{{ resource.alt }}"/></p>
<p>{{ resource.content }}</p>
<p>Category: {{ resource.category }}</p>
{% endif %}
{% endfor %}