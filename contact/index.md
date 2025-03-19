---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the Department of Gene Regulation and Morphogenesis at Centro Andaluz de Biología del Desarollo (CABD), recognized with the María de Maeztu distinction, inside the campus of Universidad Pablo de Olavide (UPO). We are also affiliated with Centro Superior de Investigaciones Científicas (CSIC) and our lab is located on the first floor of CABD (Lab 110).

{%
  include button.html
  type="email"
  text="fmarrea@upo.es"
  link="fmarrea@upo.es"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/ttV6ftSKTy1uRBqx9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/plazaespaña.jpg"
  caption="Plaza España, Sevilla"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/cabd.jpg"
  caption="Centro Andaluz de Biología del Desarrollo (CABD)"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
