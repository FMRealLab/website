---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. A

{% include section.html %}

## See our hihglighted publications

{% capture content %}

  {% include citation.html lookup="doi:10.1101/2024.10.10.617585" style="rich" %}

  {% include citation.html lookup="doi:10.1242/dev.201562" style="rich" %}

  {% include citation.html lookup="doi:10.1002/jez.b.23142" style="rich" %}

  {% include citation.html lookup="doi:10.1126/science.aaz2582" style="rich" %}
  
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}

{% include citation.html lookup="Open collaborative writing with Manubot" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{%
  include list.html
  data="citations"
  component="citation"
  style="rich"
%}
