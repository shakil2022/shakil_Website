---
layout: page
permalink: /teaching/
title: Teaching
#description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 4
calendar: false
---

<style>
  :root {
    --bg-deep: #080e1d;
    --bg-panel: #111a2e;
    --bg-card: #16213a;
    --border-soft: rgba(255,255,255,0.08);
    --text-main: #dde3ef;
    --text-dim: #8b93a7;
    --accent: #5b8def;
    --accent-soft: rgba(91,141,239,0.15);
  }

  .teaching,
  .courses,
  .page-content {
    font-family: 'Inter', system-ui, sans-serif;
    color: var(--text-main);
  }

  .teaching h1,
  .teaching h2,
  .teaching h3,
  .courses h1,
  .courses h2,
  .courses h3,
  .course-title {
    font-family: 'Playfair Display', serif;
    font-weight: 600;
    color: #eef1f8;
  }

  /* Course cards */
  .course,
  .course-item,
  .courses .card {
    background: var(--bg-card);
    border: 1px solid var(--border-soft);
    border-radius: 12px;
    padding: 20px 24px;
    margin-bottom: 18px;
    color: var(--text-main);
    transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
  }

  .course:hover,
  .course-item:hover,
  .courses .card:hover {
    transform: translateY(-3px);
    border-color: rgba(91, 141, 239, 0.35);
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.3);
  }

  .course-subtitle,
  .course-desc,
  .course-meta,
  .courses .text-muted {
    color: var(--text-dim) !important;
  }

  /* Links */
  .teaching a,
  .courses a {
    color: var(--accent);
    text-decoration: none;
    border-bottom: 1px solid rgba(91,141,239,0.3);
  }

  .teaching a:hover,
  .courses a:hover {
    border-bottom-color: var(--accent);
  }

  /* Calendar widget container */
  .calendar,
  #calendar {
    background: var(--bg-panel);
    border: 1px solid var(--border-soft);
    border-radius: 12px;
    padding: 16px;
    margin-bottom: 30px;
  }

  hr,
  .divider {
    border-top: 1px solid var(--border-soft);
  }
</style>

{% include calendar.liquid calendar_id='test@gmail.com' timezone='Asia/Shanghai' %}

{% include courses.liquid %}

<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2026 Md. Shakil Ahmed. All rights reserved.
    </p>
  </div>
</footer>