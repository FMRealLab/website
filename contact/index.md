---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.a

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/upo-logo.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/cabd-logo.png"
%}

{% capture col3 %}

{%
  include figure.html
  image="images/csic-logo.png"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% include section.html %}

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

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
