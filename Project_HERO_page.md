---
layout: page
title: "Project HERO"
permalink: /HERO/
---
Project HERO is a NORDFOU funded research project aimed at studying hydronic heated pavements and pavement solar collectors. Josef has been working in the project as a part of his PHD studies. 

# Live image from field station

Location Östersund

 ![Live image from the fieldstation](https://api.trafikinfo.trafikverket.se/v1/Images/RoadConditionCamera_39636092.Jpeg?)

 <a href="https://api.trafikinfo.trafikverket.se/v1/Images/RoadConditionCamera_39636092.Jpeg?type=fullsize&maxage=15" target="_blank">Link full size picture.</a>

<!-- {% for HERO in site.HERO %}
  <h2>{{ HERO.title }}</h2>
  <p>{{ HERO.content | markdownify }}</p>
{% endfor %} -->

{% for HERO in site.HERO %}
  <h3>
    <a href="{{ HERO.url }}">
      {{ HERO.title }}
    </a>

  </h3>

 
{% endfor %} 

<!--  <p>{{ HERO.content | markdownify }}</p>
  <p>{{HERO.excerpt}}</p>
  <p>{% assign excerpt = HERO.content | split: site.excerpt_separator %}
	{{ excerpt[0] }}</p> -->