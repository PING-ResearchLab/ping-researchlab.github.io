---
title: Alumni
nav:
  order: 4
  tooltip: Previous Team Members
---

# {% include icon.html icon="fa-solid fa-users" %}Alumni

We are very proud of our Alumni for PiNG labs.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

{% capture content %}

<!-- {% include figure.html image="images/zhu_pingping.jpg" %}
{% include figure.html image="images/james_gao.jpg" %}
{% include figure.html image="images/ben_taylor.jpg" %} -->

{% endcapture %}


{% include grid.html style="square" content=content %}
