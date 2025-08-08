---
layout: page
title: projects
permalink: /projects/
description: This page features my ongoing research projects and working papers. Drafts are available for feedback or questions, but are not yet recommended for citation.
nav: true
nav_order: 3
---

<div class="projects">
  <h3>Working Papers</h3>
  <div class="grid">
    {% bibliography --file working_papers --template project %}
  </div>

  <hr>

  <h3>Work in Progress</h3>
  <div class="grid">
    {% bibliography --file working_progress --template project %}
  </div>
</div>
