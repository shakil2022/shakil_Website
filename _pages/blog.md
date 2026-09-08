---
layout: page
permalink: /contact/
title: Contact
#description: Contact information and professional social media links.
nav: true
nav_order: 6
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

  .contact-page {
    max-width: 1100px;
    margin: 0 auto;
    padding: 20px 0 40px;
  }

  .contact-intro {
    max-width: 750px;
    margin: 0 auto 35px;
    text-align: center;
  }

  .contact-intro h1 {
    margin-bottom: 12px;
    font-weight: 700;
    color: #eef1f8;
  }

  .contact-intro p {
    margin-bottom: 0;
    color: var(--text-dim);
    line-height: 1.7;
  }

  .contact-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
    align-items: stretch;
  }

  .contact-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    min-height: 230px;
    padding: 30px 22px;
    text-align: center;
    border: 1px solid var(--border-soft);
    border-radius: 16px;
    background: var(--bg-card);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.25);
    transition:
      transform 0.25s ease,
      box-shadow 0.25s ease,
      border-color 0.25s ease;
  }

  .contact-card:hover {
    transform: translateY(-5px);
    border-color: rgba(91, 141, 239, 0.4);
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.35);
  }

  .contact-icon {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 58px;
    height: 58px;
    margin-bottom: 14px;
    color: var(--accent);
    font-size: 34px;
  }

  .contact-title {
    margin: 0 0 18px;
    color: #f0f3fa;
    font-size: 20px;
    font-weight: 700;
  }

  .contact-button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-height: 42px;
    padding: 9px 16px;
    border: 1px solid rgba(91, 141, 239, 0.35);
    border-radius: 7px;
    color: #a9c6ff !important;
    background: var(--accent-soft);
    text-decoration: none !important;
    font-size: 14px;
    font-weight: 600;
    line-height: 1.4;
    transition:
      background-color 0.2s ease,
      color 0.2s ease,
      transform 0.2s ease;
    word-break: break-word;
  }

  .contact-button:hover {
    background: var(--accent);
    color: #0b1120 !important;
    text-decoration: none !important;
    transform: translateY(-2px);
  }

  .contact-button.primary {
    background: var(--accent);
    color: #0b1120 !important;
  }

  .contact-button.primary:hover {
    background: #74a0f2;
  }

  .contact-details {
    margin-top: 45px;
  }

  .contact-details h2 {
    margin-bottom: 20px;
    font-weight: 700;
    color: #eef1f8;
  }

  .contact-details p {
    line-height: 1.8;
    color: var(--text-main);
  }

  .contact-details ul {
    padding-left: 20px;
  }

  .contact-details li {
    margin-bottom: 10px;
    color: var(--text-main);
  }

  @media (max-width: 768px) {
    .contact-grid {
      grid-template-columns: 1fr;
      max-width: 420px;
      margin: 0 auto;
    }

    .contact-card {
      min-height: 210px;
    }
  }

  @media (max-width: 576px) {
    .contact-page {
      padding: 10px 0 30px;
    }

    .contact-intro {
      margin-bottom: 25px;
    }

    .contact-card {
      padding: 25px 18px;
    }

    .contact-title {
      font-size: 19px;
    }

    .contact-button {
      max-width: 100%;
      font-size: 13px;
    }
  }
</style>

<div class="contact-page">

  <!-- <div class="contact-intro">
    <h1>Contact Information</h1>

    <p>
      If you would like to discuss research, academic collaboration,
      teaching, or other professional opportunities, please feel free
      to contact me through the following platforms.
    </p>
  </div> -->

  <div class="contact-grid">

    <!-- Email -->
    <div class="contact-card">

      <div>
        <div class="contact-icon">
          <i class="fas fa-envelope"></i>
        </div>

        <h3 class="contact-title">Email</h3>
      </div>

      
        href="mailto:shakil.ahmed@bubt.edu.bd"
        class="contact-button primary"
      >
        shakil.ahmed@bubt.edu.bd
      </a>

    </div>

    <!-- LinkedIn -->
    <div class="contact-card">

      <div>
        <div class="contact-icon">
          <i class="fab fa-linkedin"></i>
        </div>

        <h3 class="contact-title">LinkedIn</h3>
      </div>

      
        href="https://www.linkedin.com/in/md-shakil-ahmed-6482b13b3/"
        class="contact-button"
        target="_blank"
        rel="noopener noreferrer"
      >
        Connect
      </a>

    </div>

    <!-- Twitter/X -->
    <div class="contact-card">

      <div>
        <div class="contact-icon">
          <i class="fab fa-twitter"></i>
        </div>

        <h3 class="contact-title">Twitter</h3>
      </div>

      
        href="https://x.com/home"
        class="contact-button"
        target="_blank"
        rel="noopener noreferrer"
      >
        Follow
      </a>

    </div>

  </div>

</div>

<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2026 Md. Shakil Ahmed. All rights reserved.
    </p>
  </div>
</footer>