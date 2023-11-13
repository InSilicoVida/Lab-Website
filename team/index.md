---
title: Teams
nav:
  order: 3
  tooltip: About our Diverse team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our group team consist of biologists, toxicologist, bioinformaticians, and computational scientists carrying expertise from multiple domains. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

We are delighted to work with interdisciplinary background people around the world. Our team is always looking for bright researchers who like to work or collaborate with us as a team. For exploring the job or internship (online or offlie) opportunities at bachelor, master or researcher level, please feel free to contact us.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}

## Alumini<br>
Past lab members who have moved on to other institutes, organizations or company. Our group thanks them for their contribution to science and improvement of society.

{% endcapture %}

{% include grid.html style="square" content=content %}

