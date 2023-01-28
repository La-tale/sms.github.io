---
title: "Allan Lab - Publications"
layout: gridlay
excerpt: "Allan Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Submitted
{% for publi in site.data.publist_submit %}
  {{ publi.label }} {{ publi.authors }} <br />
  <em>{{ publi.issue }}</em>, {{ publi.year }}
{% endfor %}


## Journal Papers
{% for publi in site.data.publist_journal %}
  {{ publi.label }} {{ publi.authors }} <br />
  {{ publi.title }} <br />
  <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }}
{% endfor %}


## Conference Papers
{% for publi in site.data.publist_conference %}
  {{ publi.label }} {{ publi.authors }} <br />
  {{ publi.title }} <br />
  <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }}
{% endfor %}


## Patents
{% for publi in site.data.publist_patent %}
  {{ publi.label }} {{ publi.inventors }} <br />
  {{ publi.title }} <br />
  <em>{{ publi.ptype }} {{ publi.pnum }}</em>, {{ publi.year }} {{ publi.status }}
{% endfor %}


# Dissertation
Mitigating Disturbance Errors and Enhancing RMW Performance for PCM <br />
Ph.D. Dissertation, Seoul National University, Aug. 2021 <br />
Committee: Deog-Kyoon Jeong (Chair), Hyuk-Jae Lee (Advisor), Soojung Ryu, Jangwoo Kim, Jaewoong Sim
