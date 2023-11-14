---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
background: images/backgrounds/anschutz.jpg
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

InSilico vida lab is a part of the [Tecnatox](https://www.tecnatox.cat/). TecnATox is a specialized research center in the area of Technology Transfer in Toxicology, Food and Environmental Health, and member of the TECNIO Network of ACC1Ó. 
We are located at Department of Chemical Engineering, Universitat Rovira i Virgili, Tarragona, Spain. 

{%
  include figure.html
  image="images/tecnatox.jpeg"
  link="https://www.tecnatox.cat/"
  width="400px"
%}

{%
  include button.html
  type="email"
  text=site.links.email
  link=site.links.email
%}
{%
  include button.html
  type="phone"
  text="(977) 55-85-76"
  link="+34-977-55-85-76"
%}
{%
  include button.html
  type="address"
  tooltip="Location on Google Maps"
  link="https://maps.app.goo.gl/P3pAMB79xx21UGyB9"
%}

{% capture content %}
{% include figure.html image="images/contact/AHSB.jpg" %}
{% include figure.html image="images/contact/cu-aerial.jpg" %}
{% include figure.html image="images/contact/cu-photo.jpg" %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}

