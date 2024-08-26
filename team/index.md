---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

-	Introducing our highly dedicated and persistent research team, committed to advancing the field of diabetes and metabolic diseases. With expertise in epidemiology, and public health, our team is at the forefront of innovative research, working tirelessly to uncover new insights and develop effective interventions that will shape the future of healthcare.

{% include section.html %}

# Professors 

{% include list.html data="members" component="portrait" filters="role: pi" %}

# Ph.D and Master students.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
