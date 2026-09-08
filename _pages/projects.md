---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
horizontal: false
---

<style>
  :root {
    --bg-deep: #0b1120;
    --bg-panel: #111a2e;
    --bg-card: #16213a;
    --border-soft: rgba(255,255,255,0.08);
    --text-main: #dde3ef;
    --text-dim: #8b93a7;
    --accent: #5b8def;
    --accent-soft: rgba(91,141,239,0.15);
  }

  .projects,
  .projects .container {
    font-family: 'Inter', system-ui, sans-serif;
    color: var(--text-main);
  }

  .projects h1,
  .projects h2,
  .projects h3,
  .projects h4,
  .projects .card-title {
    font-family: 'Playfair Display', serif;
    font-weight: 600;
    color: #eef1f8;
  }

  /* Project cards */
  .projects .card {
    background: var(--bg-card);
    border: 1px solid var(--border-soft);
    border-radius: 12px;
    color: var(--text-main);
    transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
  }

  .projects .card:hover {
    transform: translateY(-4px);
    border-color: rgba(91, 141, 239, 0.35);
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.3);
  }

  .projects .card-subtitle,
  .projects .card-text,
  .projects .text-muted {
    color: var(--text-dim) !important;
  }

  /* Links inside cards */
  .projects .card a,
  .projects a.stretched-link {
    color: var(--accent);
    text-decoration: none;
    border-bottom: 1px solid rgba(91,141,239,0.3);
  }

  .projects .card a:hover {
    border-bottom-color: var(--accent);
  }

  /* Tags / badges (e.g. category, year) */
  .projects .badge,
  .projects .tag {
    background: var(--accent-soft);
    color: #a9c6ff;
    border: 1px solid rgba(91,141,239,0.25);
    border-radius: 8px;
    font-weight: 500;
  }

  /* Category / importance dividers, if theme renders them */
  .projects hr,
  .projects .divider {
    border-top: 1px solid var(--border-soft);
  }
</style>

<div class="projects">

  {% assign sorted_projects = site.projects | sort: "importance" %}

  {% if page.horizontal %}

    <div class="container">
      <div class="row row-cols-1 row-cols-md-2">

        {% for project in sorted_projects %}
          {% include projects_horizontal.liquid %}
        {% endfor %}

      </div>
    </div>

  {% else %}

    <div class="row row-cols-1 row-cols-md-3">

      {% for project in sorted_projects %}
        {% include projects.liquid %}
      {% endfor %}

    </div>

  {% endif %}

</div>

<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2026 Md. Shakil Ahmed. All rights reserved.
    </p>
  </div>
</footer>