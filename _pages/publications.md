---
title: "HLEE - Publications"
layout: gridlay
excerpt: "Allan Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications (^ denotes co-first author)

## Submitted
<!--
{% for publi in site.data.publist_submit %}
  {{ publi.label }} {{ publi.authors }} <br />
  <em>{{ publi.issue }}</em>, {{ publi.year }}
{% endfor %}
-->

## Conference Papers
{% for publi in site.data.publist_conference %}
  {{ publi.label }} {{ publi.authors }} <br />
  <a href="{{ publi.tlink }}">{{ publi.title }}</a> <br />
  <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }}
{% endfor %}


## Journal Papers
{% for publi in site.data.publist_journal %}
  {{ publi.label }} {{ publi.authors }} <br />
  <a href="{{ publi.tlink }}">{{ publi.title }}</a> <br />
  <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }}
{% endfor %}


## Patents
{% for publi in site.data.publist_patent %}
  {{ publi.label }} {{ publi.inventors }} <br />
  {{ publi.title }} <br />
  <em>{{ publi.ptype }} {{ publi.pnum }}</em>, {{ publi.year }} {{ publi.status }}
{% endfor %}


## Talks
{% for publi in site.data.publist_talk %}
  {{ publi.label }} {{ publi.title }} <br />
  <em>{{ publi.venue }}</em>, {{ publi.year }}
{% endfor %}


# Dissertation
Mitigating Disturbance Errors and Enhancing RMW Performance for PCM <br />
Ph.D. Dissertation, Seoul National University, Aug. 2021 <br />
Committee: Deog-Kyoon Jeong (Chair), Hyuk-Jae Lee (Advisor), Soojung Ryu, Jangwoo Kim, Jaewoong Sim
