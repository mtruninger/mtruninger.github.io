---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---

<div class="publications">

<h2>Peer-Reviewed Journal Articles</h2>
{% bibliography --query @article %}

<h2>Conference Proceedings</h2>
{% bibliography --query @inproceedings %}

</div>
