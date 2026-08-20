---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

C-VAIL is small, new, and growing fast. We're building a team united by three values: enthusiasm for tackling healthcare's toughest challenges, the energy to turn ideas into impact, and the focus to do the work right. If you want to help shape a lab from the ground up and build AI that actually helps patients, we're looking for you.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}