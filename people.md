---
layout: default
title:  "Welcome to Jekyll!"
date:   2016-02-12 17:50:00
categories: main
---

# The Team

{% for member in site.data.team %}
  {% if member.github == "" %}
  {{ member.name }}  
  _{{ member.email }}_
  {% else %}
  {{ member.name }}  
  _{{ member.email }}_  
  [github.com/{{member.github}}](https://github.com/{{member.github}})
  {% endif %}
{% endfor %}

# Faculty Coaching

{% for member in site.data.faculty %}
  {{ member.name }}  
  _{{ member.email }}_ 
{% endfor %}

# Sponsor

{% for member in site.data.sponsors %}
  {{ member.name }}  
  _{{ member.email }}_ 
{% endfor %}
