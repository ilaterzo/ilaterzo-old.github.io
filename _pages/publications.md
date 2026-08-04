---
layout: page
permalink: /research/
title: research
description: 
nav: true
nav_order: 2
---

<style>
ol.bibliography { list-style: none; padding-left: 0; }
ol.bibliography .col.col-sm-2.abbr { display: none; }
ol.bibliography li .row { margin-left: 0; }
ol.bibliography .col-sm-8 { max-width: 100%; flex: 0 0 100%; padding-left: 0; }
ol.bibliography li .hidden { max-height: 0; overflow: hidden; transition: max-height 0.15s; }
ol.bibliography li .hidden.open { max-height: 100em; transition: max-height 0.15s; }
</style>

{% bibliography -f papers %}
