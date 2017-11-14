---
layout: default
---

### [](#header-3) About
I am a PhD student at the [Laboratory for Software Technology](http://www.lst.inf.ethz.ch)-
Institute of Computer Systems, of ETH Zurich, 
under the supervision of Prof. [Thomas Gross](http://www.lst.inf.ethz.ch/people/trg.html).
My main research interests are automatic performance bug detection, and compilation techniques 
for dynamic languages, more specifically JavaScript.

I hold a MSc. degree (2010) from the University of Lugano (USI) and a BSc. degree (2008) from the 
University of Applied Sciences of Southern Switzerland (SUPSI).
Before joining ETH I spent time in the [Motion Analysis Laboratory](http://srh-mal.net/)
at Spaulding Rehabilitation Hospital (Boston, MA), and in the Networking Laboratory at SUPSI 
(Manno, Switzerland).

### [](#header-3) Publications
{% for p in site.pages %}
{% if p.type == 'publication' %}
   |:-------------|
   | ***{{ p.title }}*** |
   | {{ p.authors }} |
   | {{ p.conf }} -- [paper]({{ p.pdf }}), [implementation]({{ p.code }})|
{% endif %}
{% endfor %}
         
### [](#header-3) Teaching

|:-------------|:-------------| 
| Introduction to programming | FS 2016 |
| Compiler Design|  SS 2012-2015, FS 2017 | 
| Advanced Compiler Design |  FS 2012-2016 | 
        
### [](#header-3) Student Projects
If you are interested in doing a semester/master/diploma project, please take a look here for a 
list of [project proposals](http://www.lst.inf.ethz.ch/education/student-projects.html).
You are welcome to come to my office or write an e-mail if you need more information about one of the listed projects.
