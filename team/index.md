---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html dark=true %}

Our lab brings together a dynamic team of both experimental and computational members. This hybrid approach encourages teamwork, combining different perspectives to decode the complexities of mole evolutionary traits.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/Coffee_time.png" width="400px" caption="Our lab’s coffee machine: the only one who truly understands our need for constant _stimulation_!" %}

{% include figure.html image="images/Casual_lab.png" width="400px" caption="Nacho caught doing experiments... or just pretending!" %}

{% include figure.html image="images/Casual_compulab.png" width="400px" caption=" Casually caught Rubén analyzing scRNA-seq data... this moment was _absolutely_ not planned for the photo" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
