---
layout: page
title: Projects
description: Projects that i have been involved in one way or another. Developing, maintaining or planning.
---

<div class="projects">
  {% for project in site.projects %}
  <div>
    <h2>
      <a href="{{ project.website }}">
        {{ project.title }}
      </a>
    </h2>
    <span class="project-tagline post-date">
        {{ project.tagline }}
    </span>

    {{ project.content }}

  </div>
  {% endfor %}
</div>
