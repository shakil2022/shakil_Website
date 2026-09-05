---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

  {% bibliography %}

</div>


<!-- =========================================================
     COMPLETE LIST
     ========================================================= -->

<section class="complete-list-section">

  <h2 class="complete-list-title">Complete List</h2>

  <div class="profile-links-grid">

    <!-- Google Scholar -->
    <a
      href="https://scholar.google.com/citations?user=YOUR_GOOGLE_SCHOLAR_ID"
      class="profile-card"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Google Scholar Profile"
    >
      <div class="profile-card-icon">
        <i class="fas fa-graduation-cap"></i>
      </div>

      <div class="profile-card-content">
        <span>Google Scholar</span>
      </div>
    </a>

   <!-- ResearchGate -->
    <a
      href="https://www.researchgate.net/profile/Md-Ahmed-231/research"
      class="profile-card"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="ResearchGate Profile"
    >
      <div class="profile-card-icon">
        <i class="fab fa-researchgate"></i>
      </div>

      <div class="profile-card-content">
        <span>ResearchGate</span>
      </div>
    </a>
    <!-- ORCID -->
    <a
      href="https://orcid.org/0009-0005-5684-4151"
      class="profile-card"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="ORCID Profile"
    >
      <div class="profile-card-icon">
        <i class="fab fa-orcid"></i>
      </div>

      <div class="profile-card-content">
        <span>ORCID</span>
      </div>
    </a>


 

  </div>

</section>


<!-- =========================================================
     COMPLETE LIST CSS
     ========================================================= -->

<style>

.complete-list-section {
  width: 100%;
  margin-top: 80px;
  padding-top: 50px;
  padding-bottom: 30px;
  border-top: 1px solid rgba(255, 255, 255, 0.15);
}


/* Section heading */

.complete-list-title {
  text-align: center;
  margin-top: 0;
  margin-bottom: 40px;
  font-size: 32px;
  font-weight: 700;
  line-height: 1.3;
}


/* Profile card layout */

.profile-links-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 24px;
  width: 100%;
}


/* Profile card */

.profile-card {
  display: flex;
  align-items: center;
  width: 100%;
  min-height: 80px;
  padding: 22px 24px;
  box-sizing: border-box;
  border: 1px solid rgba(255, 255, 255, 0.18);
  border-radius: 10px;
  color: inherit;
  text-decoration: none !important;
  transition:
    transform 0.25s ease,
    border-color 0.25s ease,
    background-color 0.25s ease,
    box-shadow 0.25s ease;
}


/* Hover effect */

.profile-card:hover {
  transform: translateY(-4px);
  border-color: rgba(255, 255, 255, 0.40);
  background-color: rgba(255, 255, 255, 0.035);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.12);
  text-decoration: none !important;
}


/* Icon */

.profile-card-icon {
  width: 48px;
  height: 48px;
  flex: 0 0 48px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 26px;
  opacity: 0.80;
}


/* ORCID and ResearchGate icons */

.profile-card-icon .fa-orcid,
.profile-card-icon .fa-researchgate {
  font-size: 29px;
}


/* Text */

.profile-card-content {
  display: flex;
  align-items: center;
  margin-left: 18px;
}

.profile-card-content span {
  font-size: 18px;
  font-weight: 600;
  line-height: 1.4;
}


/* Mobile */

@media (max-width: 768px) {

  .complete-list-section {
    margin-top: 60px;
    padding-top: 40px;
  }

  .complete-list-title {
    font-size: 28px;
    margin-bottom: 30px;
  }

  .profile-links-grid {
    grid-template-columns: 1fr;
    gap: 18px;
  }

  .profile-card {
    min-height: 75px;
    padding: 20px;
  }

  .profile-card-content span {
    font-size: 17px;
  }

}


/* Small mobile */

@media (max-width: 480px) {

  .complete-list-title {
    font-size: 26px;
  }

  .profile-card {
    padding: 18px;
  }

  .profile-card-icon {
    width: 42px;
    height: 42px;
    flex-basis: 42px;
    font-size: 23px;
  }

  .profile-card-content {
    margin-left: 14px;
  }

  .profile-card-content span {
    font-size: 16px;
  }

}

</style>


<!-- Footer -->

<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2024 Md. Akmol Masud. All rights reserved.
    </p>
  </div>
</footer>