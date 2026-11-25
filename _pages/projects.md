---
layout: page
title: projects
permalink: /projects/
description: Working papers. Comments welcome. Please cite the latest version linked below.
nav: true
nav_order: 3
---

<div class="projects">
  <h3>Working Papers</h3>
  <div class="project-list">
    {% bibliography --file working_papers --template project %}
  </div>

  <hr>

  <h3>Work in Progress</h3>
  <div class="project-list">
    {% bibliography --file working_progress --template project %}
  </div>
</div>
