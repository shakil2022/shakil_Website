---
layout: page
permalink: /contact/
title: Contact
#description: Contact information and professional social media links.
nav: true
nav_order: 6
---

<style>
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
  }

  .contact-intro p {
    margin-bottom: 0;
    color: var(--global-text-color-light);
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
    border: 1px solid rgba(150, 170, 220, 0.35);
    border-radius: 16px;
    background: linear-gradient(
      135deg,
      rgba(38, 65, 105, 0.95),
      rgba(25, 48, 82, 0.95)
    );
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.12);
    transition:
      transform 0.25s ease,
      box-shadow 0.25s ease,
      border-color 0.25s ease;
  }

  .contact-card:hover {
    transform: translateY(-5px);
    border-color: rgba(180, 200, 240, 0.7);
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.2);
  }

  .contact-icon {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 58px;
    height: 58px;
    margin-bottom: 14px;
    color: #b8c5f0;
    font-size: 34px;
  }

  .contact-title {
    margin: 0 0 18px;
    color: #ffffff;
    font-size: 20px;
    font-weight: 700;
  }

  .contact-button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-height: 42px;
    padding: 9px 16px;
    border: 1px solid #aebce8;
    border-radius: 7px;
    color: #dce5f5 !important;
    background: transparent;
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
    background: #aebce8;
    color: #172746 !important;
    text-decoration: none !important;
    transform: translateY(-2px);
  }

  .contact-button.primary {
    background: #aebce8;
    color: #172746 !important;
  }

  .contact-button.primary:hover {
    background: #c2cdf0;
  }

  .contact-details {
    margin-top: 45px;
  }

  .contact-details h2 {
    margin-bottom: 20px;
    font-weight: 700;
  }

  .contact-details p {
    line-height: 1.8;
  }

  .contact-details ul {
    padding-left: 20px;
  }

  .contact-details li {
    margin-bottom: 10px;
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

      <a
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

      <a
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

      <a
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