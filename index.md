---
layout: default
---

### [](#header-4) About

I am a Post-Doc at the [Laboratory for Software Technology](http://www.lst.inf.ethz.ch) of ETH Zurich. 
My main research interests are program analysis and program synthesis for automatic performance anomalies detection.

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
            
### [](#header-3) Teaching

|:-------------|:-------------| 
| Introduction to programming | FS 2016, FS 2018 |
| Compiler Design | FS 2012-2015, SS 2017, SS 2018 | 
| Advanced Compiler Design | SS 2012-2016, FS 2017 | 
        
### [](#header-4) Student Projects
If you are interested in doing a semester/master/diploma project, please take a look here for a 
list of [project proposals](http://www.lst.inf.ethz.ch/education/student-projects.html).
You are welcome to come to my office or write an e-mail if you need more information about one of the listed projects.
