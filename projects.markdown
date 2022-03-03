---
layout: page
title: Projects
group: "navigation"
id: "projects"
---

<!-- # Research Projects
-->

## Current Projects

{% include current_projects %}

## Recently Completed Projects

* [LearnedIndex]({{ site.baseurl }}/projects/pli) Learned Distribution Indices
* [DBCarving]({{ site.baseurl }}/projects/carving/) Provenance Issues in Forensic Analysis

## Papers

{% capture dblp_url %}{{ site.data.faculty | map: 'dblp' | join: '|' }}{% endcapture %}

<p><a href="//dblp.uni-trier.de/search/publ?q={{ dblp_url }}" target="_blank">View in new window</a></p>
<iframe class="papers-iframe" src="//dblp.uni-trier.de/search/publ?q={{ dblp_url }}"></iframe>
