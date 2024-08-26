---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Introducing our highly dedicated and persistent research team, committed to advancing the field of diabetes and metabolic diseases. With expertise in epidemiology, and public health, our team is at the forefront of innovative research, working tirelessly to uncover new insights and develop effective interventions that will shape the future of healthcare.

{% include section.html %}

## Professors 

{% include list.html data="members" component="portrait" filters="role: pi" %}

## Ph.D and Master students

{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

## Collaborations


{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
