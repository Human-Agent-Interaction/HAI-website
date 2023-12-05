---
title: People
nav:
  order: 3
#  tooltip: About our team
---

{% include icon.html icon="fa-solid fa-users" %} Principal Investigator
{% include list.html data="members" component="portrait" filters="role: PI" %}

{% include icon.html icon="fa-solid fa-users" %} PhD Students
{% include list.html data="members" component="portrait" filters="role: PhD" %}

{% include icon.html icon="fa-solid fa-users" %} MS Students
{% include list.html data="members" component="portrait" filters="role: MS" %}

{% include icon.html icon="fa-solid fa-users" %} Undergraduate Students
{% include list.html data="members" component="portrait" filters="role: UG" %}

{% include icon.html icon="fa-solid fa-users" %} Staff
{% include list.html data="members" component="portrait" filters="role: staff" %}

{% include icon.html icon="fa-solid fa-users" %} Collaborators
{% include list.html data="members" component="portrait" filters="role: collaborator" %}