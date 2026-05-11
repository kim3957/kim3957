---
title: Publications
layout: publications
sitemap: true
description: "Journal articles and conference publications by Eugene Kim and collaborators."
permalink: /publications/
---

## Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card" id="pubList">
<h3>Journal Articles</h3>

{% bibliography --query @article %}

<h3>Conference Proceedings</h3>

{% bibliography --query @inproceedings %}
</div>
