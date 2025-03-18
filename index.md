---
---

# **Gene Regulation and Evolution**

An engaging 1-3 sentence description of your lab.


{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Newborns.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Adult_Mole.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/foto-grupo-Real.png"
  link="team"
  title="Our Team"
  text=text
%}

{% include section.html %}

## Funding

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

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/csic-logo.png"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
