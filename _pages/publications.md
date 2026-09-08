---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

---

layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
------------

<!-- =========================================================
     PUBLICATIONS
     ========================================================= -->

<div class="publications academic-publications">

{% include bib_search.liquid %}

{% bibliography %}

</div>

<!-- =========================================================
     ACADEMIC PROFILE LINKS
     ========================================================= -->

<section class="publication-profiles">

  <h2 class="publication-profiles-title">Academic Profiles</h2>

  <div class="publication-profile-links">

```
<!-- Google Scholar -->
<a
  href="https://scholar.google.com/citations?user=jIomJygAAAAJ&hl=en"
  class="publication-profile-link"
  target="_blank"
  rel="noopener noreferrer"
>
  <i class="fas fa-graduation-cap"></i>
  <span>Google Scholar</span>
</a>


<!-- ResearchGate -->
<a
  href="https://www.researchgate.net/profile/Md-Ahmed-231/research"
  class="publication-profile-link"
  target="_blank"
  rel="noopener noreferrer"
>
  <i class="fab fa-researchgate"></i>
  <span>ResearchGate</span>
</a>


<!-- ORCID -->
<a
  href="https://orcid.org/0009-0005-5684-4151"
  class="publication-profile-link"
  target="_blank"
  rel="noopener noreferrer"
>
  <i class="fab fa-orcid"></i>
  <span>ORCID</span>
</a>
```

  </div>

</section>

<!-- =========================================================
     PUBLICATION PAGE CSS
     Same visual style as about.md
     ========================================================= -->

<style>

/* =========================================================
   COLOR SYSTEM
   Taken from the About page
   ========================================================= */

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


/* =========================================================
   GLOBAL BOX SIZING
   ========================================================= */

.academic-publications *,
.publication-profiles * {

  box-sizing: border-box;

}


/* =========================================================
   MAIN PUBLICATION CONTAINER
   ========================================================= */

.academic-publications {

  width: 100% !important;

  max-width: none !important;

  margin: 0 !important;

  padding: 0 !important;

  color: var(--text-main);

  font-family: 'Inter', system-ui, sans-serif;

  line-height: 1.7;

}


/* =========================================================
   BIBLIOGRAPHY
   ========================================================= */

.academic-publications .bibliography {

  width: 100% !important;

  margin: 0 !important;

  padding: 0 !important;

  list-style: none !important;

}


/* =========================================================
   REMOVE AL-FOLIO THUMBNAIL / ABBREVIATION COLUMN
   ========================================================= */

/*
   This is the important part.

   al-folio can create a left-side column for
   publication thumbnails / abbreviations.

   We completely remove it so there is no
   unnecessary empty space before the year/publication.
*/

.academic-publications .abbr,
.academic-publications .preview {

  display: none !important;

}


/* Remove Bootstrap thumbnail columns */

.academic-publications .bibliography .col-sm-2,
.academic-publications .bibliography .col-md-2,
.academic-publications .bibliography .col-lg-2 {

  display: none !important;

}


/* =========================================================
   BIBLIOGRAPHY ROW
   ========================================================= */

.academic-publications .bibliography .row {

  width: 100% !important;

  margin: 0 !important;

  padding: 0 !important;

}


/* Remove Bootstrap gutters */

.academic-publications .bibliography .row > div {

  padding-left: 0 !important;

  padding-right: 0 !important;

}


/* =========================================================
   YEAR + PUBLICATION LAYOUT
   ========================================================= */

/*
   The bibliography year is positioned on the LEFT.

   There is no large al-folio thumbnail margin.

   Year column:
       72px

   Publication content:
       remaining available width
*/

.academic-publications .bibliography h2,
.academic-publications .bibliography h3,
.academic-publications .bibliography .year {

  float: left !important;

  width: 72px !important;

  min-width: 72px !important;

  margin: 34px 0 0 0 !important;

  padding: 0 !important;

  border: none !important;

  color: var(--text-dim);

  font-family: 'Inter', system-ui, sans-serif;

  font-size: 15px;

  font-weight: 600;

  line-height: 1.5;

  text-align: left;

}


/*
   The publication entries occupy the remaining
   page width.

   This is NOT the old al-folio left thumbnail margin.
   The only left space is the small year column.
*/

.academic-publications .bibliography > li {

  width: calc(100% - 72px) !important;

  margin-left: 72px !important;

  margin-right: 0 !important;

  padding: 25px 0 24px !important;

  border-bottom: 1px solid var(--border-soft);

  position: relative;

  display: block !important;

  clear: none !important;

}


/*
   Clear the first publication after the year.
*/

.academic-publications .bibliography > li:first-of-type {

  padding-top: 8px !important;

}


/* =========================================================
   REMOVE EXTRA PUBLICATION COLUMN INDENTATION
   ========================================================= */

.academic-publications .bibliography .col-sm-8,
.academic-publications .bibliography .col-sm-10,
.academic-publications .bibliography .col-md-8,
.academic-publications .bibliography .col-md-10,
.academic-publications .bibliography .col-lg-8,
.academic-publications .bibliography .col-lg-10 {

  width: 100% !important;

  max-width: 100% !important;

  margin-left: 0 !important;

  padding-left: 0 !important;

  padding-right: 0 !important;

}


/*
   Catch any nested Bootstrap column.
*/

.academic-publications .bibliography li [class*="col-"] {

  padding-left: 0 !important;

  padding-right: 0 !important;

}


/* =========================================================
   YEAR VISUAL STYLE
   ========================================================= */

.academic-publications .bibliography h2::after,
.academic-publications .bibliography h3::after,
.academic-publications .bibliography .year::after {

  content: none !important;

}


/* =========================================================
   PUBLICATION TITLE
   Same Playfair Display style as About page headings
   ========================================================= */

.academic-publications .title {

  display: block;

  margin: 0 0 8px 0;

  padding: 0;

  color: #f0f3fa;

  font-family: 'Playfair Display', serif;

  font-size: 17px;

  font-weight: 600;

  line-height: 1.5;

  text-decoration: none;

}


/* Title hover */

.academic-publications .title:hover {

  color: var(--accent);

  text-decoration: none;

}


/* =========================================================
   AUTHORS
   Same Inter style as About page
   ========================================================= */

.academic-publications .author {

  margin: 0 0 6px 0;

  padding: 0;

  color: var(--text-main);

  font-family: 'Inter', system-ui, sans-serif;

  font-size: 14px;

  font-weight: 500;

  line-height: 1.6;

}


/* =========================================================
   JOURNAL / CONFERENCE / PERIODICAL
   ========================================================= */

.academic-publications .periodical {

  margin: 0 0 12px 0;

  padding: 0;

  color: var(--text-dim);

  font-family: 'Inter', system-ui, sans-serif;

  font-size: 13px;

  font-weight: 400;

  line-height: 1.6;

}


/* Journal name */

.academic-publications .periodical em {

  color: #a9c6ff;

  font-style: italic;

}


/* =========================================================
   PUBLICATION LINKS
   ========================================================= */

.academic-publications .links {

  display: flex;

  flex-wrap: wrap;

  align-items: center;

  gap: 8px;

  margin: 5px 0 0 0;

  padding: 0;

}


/* =========================================================
   PUBLICATION BUTTONS
   ========================================================= */

.academic-publications .links a {

  display: inline-flex;

  align-items: center;

  justify-content: center;

  min-height: 28px;

  padding: 5px 10px;

  border: 1px solid rgba(91,141,239,0.25);

  border-radius: 8px;

  background: var(--accent-soft);

  color: #a9c6ff !important;

  font-family: 'Inter', system-ui, sans-serif;

  font-size: 11px;

  font-weight: 500;

  line-height: 1.2;

  text-transform: uppercase;

  text-decoration: none !important;

  transition:
    background-color 0.2s ease,
    border-color 0.2s ease,
    color 0.2s ease;

}


/* Button hover */

.academic-publications .links a:hover {

  background: rgba(91,141,239,0.18);

  border-color: rgba(91,141,239,0.45);

  color: #ffffff !important;

  text-decoration: none !important;

}


/* =========================================================
   BIBTEX
   ========================================================= */

.academic-publications .bibtex-button,
.academic-publications .btn {

  font-family: 'Inter', system-ui, sans-serif;

  font-size: 11px;

}


/* BibTeX content */

.academic-publications .bibtex {

  margin-top: 10px;

  font-size: 12px;

}


/* =========================================================
   BIB SEARCH
   ========================================================= */

.academic-publications .bib-search {

  width: 100% !important;

  margin: 0 0 28px 0;

  padding: 0 !important;

}


/* =========================================================
   ACADEMIC PROFILE SECTION
   ========================================================= */

.publication-profiles {

  width: 100%;

  margin-top: 55px;

  padding-top: 32px;

  padding-bottom: 25px;

  border-top: 1px solid var(--border-soft);

}


/* =========================================================
   PROFILE SECTION TITLE
   ========================================================= */

.publication-profiles-title {

  margin: 0 0 20px 0;

  padding: 0;

  color: #eef1f8;

  font-family: 'Inter', system-ui, sans-serif;

  font-size: 17px;

  font-weight: 700;

  letter-spacing: 0.02em;

  line-height: 1.4;

  text-transform: uppercase;

}


/* =========================================================
   PROFILE LINKS
   ========================================================= */

.publication-profile-links {

  display: flex;

  flex-wrap: wrap;

  align-items: center;

  gap: 10px;

  margin: 0;

  padding: 0;

}


/* =========================================================
   PROFILE LINK
   ========================================================= */

.publication-profile-link {

  display: inline-flex;

  align-items: center;

  justify-content: center;

  gap: 8px;

  min-height: 32px;

  padding: 7px 13px;

  border: 1px solid rgba(255,255,255,0.14);

  border-radius: 18px;

  background: rgba(91,141,239,0.10);

  color: #dce5f5 !important;

  font-family: 'Inter', system-ui, sans-serif;

  font-size: 12px;

  font-weight: 500;

  line-height: 1.2;

  text-decoration: none !important;

  transition: all 0.2s ease;

}


/* Profile icon */

.publication-profile-link i {

  font-size: 13px;

  color: var(--accent);

}


/* Profile hover */

.publication-profile-link:hover {

  background: rgba(91,141,239,0.18);

  border-color: rgba(91,141,239,0.35);

  color: #ffffff !important;

  text-decoration: none !important;

}


.publication-profile-link:hover i {

  color: #ffffff;

}


/* =========================================================
   DARK MODE
   ========================================================= */

html[data-theme="dark"] .academic-publications .title {

  color: #f0f3fa;

}


html[data-theme="dark"] .academic-publications .author {

  color: var(--text-main);

}


html[data-theme="dark"] .academic-publications .periodical {

  color: var(--text-dim);

}


html[data-theme="dark"] .academic-publications .bibliography > li {

  border-bottom-color: var(--border-soft);

}


/* =========================================================
   LIGHT MODE
   ========================================================= */

html[data-theme="light"] .academic-publications .title {

  color: #202936;

}


html[data-theme="light"] .academic-publications .author {

  color: #4e5968;

}


html[data-theme="light"] .academic-publications .periodical {

  color: #687385;

}


html[data-theme="light"] .academic-publications .bibliography > li {

  border-bottom-color: rgba(0,0,0,0.12);

}


html[data-theme="light"] .academic-publications .bibliography h2,
html[data-theme="light"] .academic-publications .bibliography h3,
html[data-theme="light"] .academic-publications .bibliography .year {

  color: #687385;

}


/* =========================================================
   TABLET
   ========================================================= */

@media (max-width: 768px) {

  .academic-publications .bibliography h2,
  .academic-publications .bibliography h3,
  .academic-publications .bibliography .year {

    width: 62px !important;

    min-width: 62px !important;

    font-size: 14px;

  }


  .academic-publications .bibliography > li {

    width: calc(100% - 62px) !important;

    margin-left: 62px !important;

    padding: 22px 0 21px !important;

  }


  .academic-publications .title {

    font-size: 16px;

  }


  .academic-publications .author {

    font-size: 13px;

  }


  .academic-publications .periodical {

    font-size: 12.5px;

  }


  .publication-profiles {

    margin-top: 45px;

  }

}


/* =========================================================
   MOBILE
   ========================================================= */

@media (max-width: 480px) {

  /*
     On small screens the year becomes a normal heading
     so the publication text has enough space.
  */

  .academic-publications .bibliography h2,
  .academic-publications .bibliography h3,
  .academic-publications .bibliography .year {

    float: none !important;

    display: block !important;

    width: 100% !important;

    min-width: 0 !important;

    margin: 28px 0 8px 0 !important;

    padding: 0 !important;

    font-size: 14px;

    line-height: 1.4;

  }


  .academic-publications .bibliography > li {

    width: 100% !important;

    margin-left: 0 !important;

    padding: 17px 0 18px !important;

  }


  .academic-publications .title {

    font-size: 15px;

    line-height: 1.5;

  }


  .academic-publications .author {

    font-size: 12.5px;

  }


  .academic-publications .periodical {

    font-size: 12px;

  }


  .academic-publications .links {

    gap: 6px;

  }


  .academic-publications .links a {

    min-height: 27px;

    padding: 5px 8px;

    font-size: 10px;

  }


  .publication-profiles {

    margin-top: 40px;

    padding-top: 25px;

  }


  .publication-profiles-title {

    font-size: 16px;

  }


  .publication-profile-links {

    gap: 8px;

  }


  .publication-profile-link {

    font-size: 11px;

    padding: 6px 10px;

  }

}


/* =========================================================
   ACCESSIBILITY
   ========================================================= */

.academic-publications a:focus-visible,
.publication-profile-link:focus-visible {

  outline: 2px solid var(--accent);

  outline-offset: 3px;

}


/* =========================================================
   FOOTER
   ========================================================= */

.site-footer {

  margin-top: 55px;

}

</style>

<!-- =========================================================
     FOOTER
     ========================================================= -->

<footer class="site-footer">

  <div class="container text-center">

```
<p class="mb-0">

  © 2026 Md. Shakil Ahmed. All rights reserved.

</p>
```

  </div>

</footer>
