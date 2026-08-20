---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

C-VAIL is small, new, and growing fast. We're building a team united by three values: enthusiasm for tackling healthcare's toughest challenges, the energy to turn ideas into impact, and the focus to do the work right. If you want to help shape a lab from the ground up and build AI that actually helps patients, we're looking for you.

{% capture content %}
We do not currently have funded graduate research assistantship positions open. That said, undergraduate and graduate students interested in gaining hands-on research experience are more than welcome to reach out and explore opportunities to work with us.
{% endcapture %}

{% include alert.html type="info" content=content %}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}