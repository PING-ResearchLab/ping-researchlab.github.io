---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team at the PiNG Lab is a diverse group of passionate researchers, graduate students, and collaborators driven by a shared mission to advance intelligent systems. Under the leadership of Dr. Pingping Zhu, we combine expertise in electrical engineering, computer science, and robotics to tackle cutting-edge challenges in computer vision, drone control, and deep learning.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}


{% include section.html background="images/background.jpg" dark=true %}

Interested in working at the intersection of AI, robotics, and intelligent control? The PiNG Lab welcomes motivated students and collaborators to join our research efforts. Whether you're an undergraduate, graduate student, or industry partner, there are opportunities to contribute to cutting-edge projects in computer vision, swarm robotics, and deep learning. Reach out to learn how you can get involved!

{% include section.html %}

{% capture content %}

{% include figure.html image="images/zhu_pingping.jpg" %}
{% include figure.html image="images/james_gao.jpg" %}
{% include figure.html image="images/ben_taylor.jpg" %}

{% endcapture %}


{% include grid.html style="square" content=content %}
