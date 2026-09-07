---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

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

    <!-- Google Scholar -->
    <a
      href="https://scholar.google.com/citations?user=YOUR_GOOGLE_SCHOLAR_ID"
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

  </div>

</section>


<!-- =========================================================
     PUBLICATION PAGE CSS
     ========================================================= -->

<style>

/* =========================================================
   MAIN PUBLICATION CONTAINER
   ========================================================= */

.academic-publications {
  width: 100%;
  max-width: 100%;
  margin: 0 auto;
}


/* =========================================================
   BIBLIOGRAPHY BASE
   ========================================================= */

.academic-publications .bibliography {
  margin: 0;
  padding: 0;
  list-style: none;
}


/* =========================================================
   YEAR HEADINGS
   ========================================================= */

.academic-publications .bibliography h2,
.academic-publications .bibliography h3,
.academic-publications .bibliography .year {
  font-family: Georgia, "Times New Roman", serif;
  color: #f0f2f5;
  font-size: 30px;
  font-weight: 700;
  line-height: 1.25;

  margin-top: 42px;
  margin-bottom: 20px;

  padding-bottom: 14px;

  border-bottom: 1px solid rgba(255, 255, 255, 0.15);
}


/* =========================================================
   INDIVIDUAL PUBLICATION
   ========================================================= */

.academic-publications .bibliography > li {
  position: relative;

  margin: 0;
  padding: 27px 0 25px;

  border-bottom: 1px solid rgba(255, 255, 255, 0.13);
}


/* Remove unnecessary first border spacing */

.academic-publications .bibliography > li:first-child {
  padding-top: 8px;
}


/* =========================================================
   PUBLICATION ROW
   ========================================================= */

.academic-publications .bibliography .row {
  margin: 0;
  padding: 0;
}


/* Remove Bootstrap column spacing */

.academic-publications .bibliography .row > div {
  padding-left: 0;
  padding-right: 0;
}


/* =========================================================
   PUBLICATION TITLE
   ========================================================= */

.academic-publications .title {
  display: block;

  margin: 0 0 9px;

  font-family: Georgia, "Times New Roman", serif;

  color: #f1f2f4;

  font-size: 18px;
  font-weight: 700;

  line-height: 1.45;

  text-decoration: none;
}


/* Title hover */

.academic-publications .title:hover {
  color: #ffffff;
  text-decoration: none;
}


/* =========================================================
   AUTHORS
   ========================================================= */

.academic-publications .author {
  margin: 0 0 7px;

  color: #d4d9e2;

  font-family:
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    Roboto,
    Arial,
    sans-serif;

  font-size: 13px;
  font-weight: 600;

  line-height: 1.5;
}


/* =========================================================
   PERIODICAL / JOURNAL / STATUS
   ========================================================= */

.academic-publications .periodical {
  margin: 0 0 13px;

  color: #9da9bb;

  font-family:
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    Roboto,
    Arial,
    sans-serif;

  font-size: 13px;

  line-height: 1.5;
}


/* Italic journal name */

.academic-publications .periodical em {
  color: #aab5c6;
}


/* =========================================================
   PUBLICATION LINKS
   ========================================================= */

.academic-publications .links {
  display: flex;
  flex-wrap: wrap;

  gap: 10px;

  margin-top: 4px;
}


/* =========================================================
   BUTTONS
   ========================================================= */

.academic-publications .links a {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  min-height: 28px;

  padding: 4px 9px;

  border: 1px solid #9eafc9;
  border-radius: 4px;

  background: transparent;

  color: #aebdd6 !important;

  font-family:
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    Roboto,
    Arial,
    sans-serif;

  font-size: 11px;
  font-weight: 500;

  line-height: 1.2;

  text-transform: uppercase;

  text-decoration: none !important;

  transition:
    color 0.2s ease,
    background-color 0.2s ease,
    border-color 0.2s ease;
}


/* Button hover */

.academic-publications .links a:hover {
  color: #ffffff !important;

  border-color: #d2dceb;

  background-color: rgba(255, 255, 255, 0.06);

  text-decoration: none !important;
}


/* =========================================================
   BIBTEX BUTTON
   ========================================================= */

.academic-publications .bibtex-button,
.academic-publications .btn {
  font-size: 11px;
}


/* =========================================================
   THUMBNAIL / IMAGE
   ========================================================= */

/*
   Hide publication thumbnails so the page follows
   the screenshot's text-focused academic structure.
*/

.academic-publications .abbr,
.academic-publications .preview {
  display: none !important;
}


/* =========================================================
   HIDE UNNECESSARY BIBTEX CONTENT
   ========================================================= */

.academic-publications .bibtex {
  margin-top: 10px;
}


/* =========================================================
   BIB SEARCH
   ========================================================= */

.academic-publications .bib-search {
  margin-bottom: 25px;
}


/* =========================================================
   ACADEMIC PROFILE SECTION
   ========================================================= */

.publication-profiles {
  width: 100%;

  margin-top: 70px;
  padding-top: 35px;
  padding-bottom: 25px;

  border-top: 1px solid rgba(255, 255, 255, 0.15);
}


/* Section heading */

.publication-profiles-title {
  margin: 0 0 25px;

  font-family: Georgia, "Times New Roman", serif;

  color: #f0f2f5;

  font-size: 24px;
  font-weight: 700;

  line-height: 1.3;
}


/* =========================================================
   PROFILE LINKS
   ========================================================= */

.publication-profile-links {
  display: flex;
  flex-wrap: wrap;

  gap: 10px;
}


/* Individual profile link */

.publication-profile-link {
  display: inline-flex;

  align-items: center;
  justify-content: center;

  gap: 8px;

  min-height: 32px;

  padding: 5px 11px;

  border: 1px solid #9eafc9;
  border-radius: 4px;

  background: transparent;

  color: #aebdd6 !important;

  font-family:
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    Roboto,
    Arial,
    sans-serif;

  font-size: 11px;
  font-weight: 500;

  text-transform: uppercase;

  text-decoration: none !important;

  transition:
    color 0.2s ease,
    background-color 0.2s ease,
    border-color 0.2s ease;
}


/* Profile icon */

.publication-profile-link i {
  font-size: 13px;
}


/* Profile hover */

.publication-profile-link:hover {
  color: #ffffff !important;

  border-color: #d2dceb;

  background-color: rgba(255, 255, 255, 0.06);

  text-decoration: none !important;
}


/* =========================================================
   DARK BLUE THEME
   ========================================================= */

/*
   These variables create the same overall color feeling
   as the screenshot while remaining compatible with
   al-folio's dark theme.
*/

body {
  --publication-heading: #f0f2f5;
  --publication-title: #f1f2f4;
  --publication-author: #d4d9e2;
  --publication-muted: #9da9bb;
  --publication-button: #aebdd6;
  --publication-border: rgba(255, 255, 255, 0.13);
}


/* =========================================================
   DARK MODE REFINEMENT
   ========================================================= */

html[data-theme="dark"] .academic-publications .title {
  color: #f1f2f4;
}

html[data-theme="dark"] .academic-publications .author {
  color: #d4d9e2;
}

html[data-theme="dark"] .academic-publications .periodical {
  color: #9da9bb;
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
  border-bottom-color: rgba(0, 0, 0, 0.12);
}

html[data-theme="light"] .academic-publications .bibliography h2,
html[data-theme="light"] .academic-publications .bibliography h3,
html[data-theme="light"] .academic-publications .bibliography .year {
  color: #202936;

  border-bottom-color: rgba(0, 0, 0, 0.14);
}


/* =========================================================
   TABLET
   ========================================================= */

@media (max-width: 768px) {

  .academic-publications .bibliography h2,
  .academic-publications .bibliography h3,
  .academic-publications .bibliography .year {
    font-size: 28px;

    margin-top: 35px;
    margin-bottom: 16px;
  }


  .academic-publications .bibliography > li {
    padding: 23px 0 22px;
  }


  .academic-publications .title {
    font-size: 17px;
  }


  .academic-publications .author,
  .academic-publications .periodical {
    font-size: 12.5px;
  }


  .publication-profiles {
    margin-top: 55px;
  }

}


/* =========================================================
   SMALL MOBILE
   ========================================================= */

@media (max-width: 480px) {

  .academic-publications .bibliography h2,
  .academic-publications .bibliography h3,
  .academic-publications .bibliography .year {
    font-size: 25px;

    margin-top: 30px;
    padding-bottom: 11px;
  }


  .academic-publications .title {
    font-size: 16px;
    line-height: 1.45;
  }


  .academic-publications .author,
  .academic-publications .periodical {
    font-size: 12px;
  }


  .academic-publications .links {
    gap: 7px;
  }


  .academic-publications .links a {
    min-height: 27px;

    padding: 4px 8px;

    font-size: 10px;
  }


  .publication-profiles-title {
    font-size: 22px;
  }


  .publication-profile-links {
    gap: 7px;
  }

}


/* =========================================================
   ACCESSIBILITY
   ========================================================= */

.academic-publications a:focus-visible,
.publication-profile-link:focus-visible {
  outline: 2px solid #b8c7df;
  outline-offset: 3px;
}

</style>


<!-- =========================================================
     FOOTER
     ========================================================= -->

<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2024 Md. Shakil Ahmed. All rights reserved.
    </p>
  </div>
</footer>