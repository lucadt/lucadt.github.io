---
layout: default
---

### [](#header-4) About

I am software engineer at [xorlab AG](https://www.xorlab.com). Previously, I was a Post-Doc at the [Laboratory for Software Technology](http://www.lst.inf.ethz.ch) (ETH Zurich). My research focused on program analysis and program synthesis for automatic performance anomalies detection.

I hold a PhD (2018) from ETH Zurich (under the supervision of Prof. Thomas Gross), a MSc. degree (2010) from the University of Lugano (USI), and a BSc. degree (2008) from the  University of Applied Sciences of Southern Switzerland (SUPSI).

Before joining ETH I spent time in the [Motion Analysis Laboratory](http://srh-mal.net/)
at Spaulding Rehabilitation Hospital (Boston, MA), and in the Networking Laboratory at SUPSI 
(Manno, Switzerland).

### [](#header-4) Research papers

{% for p in site.pages %}
{% if p.type == 'publication' %}
   |:-------------|
   | ***{{ p.title }}*** |
   | {{ p.authors }} |
   | {{ p.conf }} -- [paper]({{ p.pdf }}), [implementation]({{ p.code }})|
{% endif %}
{% endfor %}

Research papers related to my past work experiences can be found in [DBLP](http://dblp.uni-trier.de/pers/hd/t/Toffola:Luca_Della)

### [](#header-4) PhD dissertation
{% for p in site.pages %}
{% if p.type == 'dissertation' %}
   |:-------------|
   | ***{{ p.title }}*** |
   | {{ p.authors }} |
   | {{ p.conf }} -- [pdf]({{ p.pdf }})|
{% endif %}
{% endfor %}
