---
layout: splash
title: "Projects"
permalink: /projects/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/projects/projectsHeader.jpg
excerpt: Discover my diverse skillset in computer science, AI, robotics, mechanics, and electronics.
---

<div class="project-catalog">
    {% for project in site.data.projects-cards-data %}
        {% include project/project-card.html %}
    {% endfor %}
</div>