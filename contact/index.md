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
  image="images/contact/health-ai-logo.png"
  link="https://medschool.cuanschutz.edu/"
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
  text="(215) 573-2991"
  link="+1-215-573-2991"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Anschutz+Health+Sciences+Building/@39.7454721,-104.8418929,15z/data=!4m2!3m1!1s0x0:0x85f675e778fce18c?sa=X&ved=2ahUKEwjd_MfInpL6AhWEhIkEHd6WDIcQ_BJ6BAhkEAU"
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

