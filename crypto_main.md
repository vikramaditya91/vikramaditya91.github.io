---
layout: default
published: true
---
{% for post in site.posts %}
  	{% if post.crypto == 'crypto' %}
<li>
  <a href="{{ post.url }}">
    {{ post.title }}
  </a>
  - <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
</li>
{% endif %}
      
{% endfor %}
