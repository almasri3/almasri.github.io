---
layout: page
permalink: /publications/
title: publications
#description: publications by category in reverse chronological order.
nav: true
nav_order: 2

scholar:
  sort_by: year
  order: descending
---

<!-- _pages/publications.md -->

<div class="publications">

## Peer-Reviewed Articles

{% bibliography --query @article %}

## Books in Progress

{% bibliography --query @book %}

## Working Papers

{% bibliography --query @*[keywords=working] %}

## Other Publications

{% bibliography --query @*[keywords=other] %}

</div>
