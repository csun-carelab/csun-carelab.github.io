---
title: Team
nav:
  order: 2
  tooltip: The people who make it happen!
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are actively looking for graduate and undergradute students to join our research group!
Please send an email with your resume and a short description of your interests to Dr. Nemlekar at <span style="color: tomato;">heramb.nemlekar@csun.edu</span>

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=false %}

*"Scenius stands for the intelligence and the intuition of a whole cultural scene. It is the communal form of the concept of the genius." - Brian Eno*

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
