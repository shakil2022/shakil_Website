---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 6
cv_pdf: /assets/pdf/example_pdf.pdf
cv_format: rendercv
toc:
  sidebar: left
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

  body,
  .cv-page,
  .page-content {
    font-family: 'Inter', system-ui, sans-serif;
    color: var(--text-main);
    background: var(--bg-deep);
  }

  /* Headings */
  .cv-page h1,
  .cv-page h2,
  .cv-page h3,
  .cv-page h4 {
    font-family: 'Playfair Display', serif;
    font-weight: 600;
    color: #eef1f8;
  }

  /* Links */
  .cv-page a {
    color: var(--accent);
    text-decoration: none;
    border-bottom: 1px solid rgba(91,141,239,0.3);
  }

  .cv-page a:hover {
    border-bottom-color: var(--accent);
  }

  /* Sidebar TOC */
  #toc-sidebar,
  .toc-sidebar,
  nav.toc {
    background: var(--bg-panel);
    border-right: 1px solid var(--border-soft);
  }

  #toc-sidebar a,
  .toc-sidebar a,
  nav.toc a {
    color: var(--text-dim);
    border-bottom: none;
  }

  #toc-sidebar a:hover,
  .toc-sidebar a:hover,
  nav.toc a:hover,
  #toc-sidebar a.active,
  .toc-sidebar a.active {
    color: var(--accent);
  }

  /* CV entry cards / sections */
  .cv-entry,
  .entry,
  .cv-section {
    background: var(--bg-card);
    border: 1px solid var(--border-soft);
    border-radius: 12px;
    padding: 20px 24px;
    margin-bottom: 18px;
  }

  /* Dates / secondary text */
  .cv-entry .date,
  .entry .date,
  .cv-date,
  .text-muted {
    color: var(--text-dim) !important;
  }

  /* PDF download button, if theme renders one */
  .cv-download-btn,
  a.pdf-download {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 9px 16px;
    border: 1px solid rgba(91, 141, 239, 0.35);
    border-radius: 7px;
    color: #a9c6ff !important;
    background: var(--accent-soft);
    text-decoration: none !important;
    font-weight: 600;
    transition: background-color 0.2s ease, color 0.2s ease, transform 0.2s ease;
  }

  .cv-download-btn:hover,
  a.pdf-download:hover {
    background: var(--accent);
    color: #0b1120 !important;
    transform: translateY(-2px);
  }

  hr {
    border-top: 1px solid var(--border-soft);
  }
</style>