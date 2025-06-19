---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

For questions, collaborations, or more information about the PiNG (Perception Intelligence Networks Group) Lab at Marshall University, please feel free to reach out. We welcome inquiries from students, researchers, and industry partners interested in intelligent control, computer vision, drone swarm systems, and deep learning. Located in Huntington, WV, our lab is led by Dr. Pingping Zhu and is committed to advancing research in autonomous and intelligent systems.

{%
  include button.html
  type="email"
  text="zhup@marshall.edu"
  link="zhup@marshall.edu"
%}
<!-- {%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%} -->
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/aGTUbemvdBTGmLKv7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="The iconic Memorial Student Center at the heart of Marshall University’s campus."
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Aerial view of Marshall University surrounded by the vibrant town of Huntington."
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Downtown Huntington blends historic charm with a growing hub for innovation and education."
%}

{% endcapture %}

{% capture col4 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="The natural beauty of West Virginia—rolling hills, lush forests, and scenic river valleys."
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4%}

<!-- {% include section.html dark=true %} -->

<!-- {% capture col1 %}
The iconic Memorial Student Center 
at the heart of Marshall University’s campus.
{% endcapture %}

{% capture col2 %}
Aerial view of Marshall University 
surrounded by the vibrant town of Huntington.
{% endcapture %}

{% capture col3 %}
Downtown Huntington blends historic charm 
with a growing hub for innovation and education.
{% endcapture %}

{% capture col4 %}
The natural beauty of West Virginia—rolling hills, 
lush forests, and scenic river valleys.
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %} -->
