---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

We use genomics and omics approaches to explore classic EvoDevo questions, combining them with synthetic biology to validate our findings in in vivo models. 

{% include section.html %}

## See our hihglighted publications

{% capture col1 %}

{% include citation.html lookup="doi:10.1101/2024.10.10.617585" style="rich" %}

{% endcapture %}

{% capture col2 %}

{% include citation.html lookup="doi:10.1242/dev.201562" style="rich" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% capture col1 %}

{% include citation.html lookup="doi:10.1002/jez.b.23142" style="rich" %}

{% endcapture %}

{% capture col2 %}

{% include citation.html lookup="doi:10.1126/science.aaz2582" style="rich" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

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
