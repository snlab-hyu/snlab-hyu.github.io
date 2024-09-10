---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Principal Investigator
{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include section.html %}


## Current Members
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ms" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html %}

## Alumni
{% include list.html data="members" component="portrait" filters="role: alumni" %}

{% include section.html %}


{% capture content %}


{% endcapture %}

{% include grid.html style="square" content=content %}
