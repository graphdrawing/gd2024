---
# permalink: /about/
layout: single
title: "Committee"
header:
  image: /assets/images/teaser/40704_cropped.jpg
  caption: "Image credit: [**WienTourismus/Christian Stemper**](https://foto.wien.info/Bild/Imperial/45013)"
# last_modified_at: 2024-01-22
toc: true
---

{% assign data = site.data.publicity %}


## Organizing Committee

* Doris Brazda, TU Wien, Austria
* Thomas Depian, TU Wien, Austria 
* Alexander Dobler, TU Wien, Austria 
* Simon Dominik Fink, TU Wien, Austria 
* Robert Ganian, TU Wien (co-chair), Austria
* Martin Nöllenburg, TU Wien (co-chair), Austria
* Hsiang-Yun Wu, St. Pölten University of Applied Sciences, Austria


## Program Committee

* Daniel Archambault, Newcastle University
* David Auber, University of Bordeaux
* Benjamin Bach, University of Edinburgh
* Martin Balko, Charles University in Prague
* Carla Binucci, University of Perugia
* Giuseppe Di Battista, Third University of Rome
* Vida Dujmovic, University of Ottawa
* Tim Dwyer, Monash University
* David Eppstein, University of California, Irvine
* Stefan Felsner (co-chair), Technical University Berlin
* Tom Freeman, Janssen Research and Development
* Michael Hoffmann, ETH Zurich
* Seok-Hee Hong, University of Sydney
* Yifan Hu, Amazon
* Tony Huang, University of Technology Sydney
* Jonathan Klawitter, University of Auckland
* Karsten Klein (co-chair), Konstanz University
* Linda Kleist, Technische Universität Braunschweig
* Boris Klemz, University of Würzburg
* Maarten Löffler, Utrecht University
* Maurizio Patrignani, Third University of Rome
* Arnaud Sallaberry, University of Montpellier
* Manfred Scheucher, Technical University Berlin
* Alessandra Tappini, University of Perugia
* Géza Tóth, Rényi Institute, Budapest
* Torsten Ueckerdt (remote submission chair), KIT Karlsruhe
* Birgit Vogtenhuber, Graz University of Technology
* Hsiang-Yun Wu, St. Pölten University of Applied Sciences

## Contest Committee
* Sara Di Bartolomeo, University of Konstanz, Germany
* Fabian Klute (chair), UPC Barcelona, Spain
* Wouter Meulemans, TU Eindhoven, Netherlands
* Debajyoti Mondal, University of Saskatchewan, Canada
* Jules Wulms, TU Eindhoven, Netherlands

<!--
{% assign role = "" %}
{% for member in data.OC-Members %}
  {% if role != member.Role %}
    {% assign role = member.Role %}
<h3 class="oc-role"><strong>{{ member.Role }}</strong></h3>
  {% endif %}
<div style="display: inline-block; width: 45%; text-align: left;">
  {% if member.Photo == "yes" %}
<img style="border-radius: 50%" src="../../assets/images/oc/{{ member.First }}_{{ member.Given }}.jpg"
     class="circle" width="150" height="150" /><br />
  {% else %}
<img style="border-radius: 50%" src="../../assets/images/oc/nobody.jpg" width="150" height="150" /><br />
  {% endif %}
<strong>{{ member.First }} {{ member.Given }}</strong><br />
{{ member.Affiliation }}<br /><br />
</div>
{% endfor %}
-->

## Steering Committee

Please refer to [graphdrawing.org](http://graphdrawing.org/sc.html)
