---
layout: about
title: about
permalink: /

subtitle: >
  <a href="https://bubt.edu.bd/department/department-of-computer-science-engineering/faculty/profile/MDSHA">
  Lecturer</a>, Department of Computer Science and Engineering,
  Bangladesh University of Business and Technology

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false
  more_info: >

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: true
  scrollable: true
  limit: 3
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

  * {
    box-sizing: border-box;
  }

  html,
  body {
    margin: 0;
    padding: 0;
  }

  body {
    background: var(--bg-deep);
    color: var(--text-main);
    font-family: 'Inter', system-ui, sans-serif;
    line-height: 1.7;
  }

  a {
    color: var(--accent);
    text-decoration: none;
    border-bottom: 1px solid rgba(91,141,239,0.3);
  }

  a:hover {
    border-bottom-color: var(--accent);
  }

  .hero {
    position: relative;
    overflow: hidden;
    background:
      radial-gradient(
        ellipse at 20% 10%,
        rgba(91,141,239,0.10),
        transparent 60%
      ),
      var(--bg-panel);
    padding: 64px 24px 56px;
  }

  .stars {
    position: absolute;
    inset: 0;
    background-image:
      radial-gradient(1px 1px at 10% 20%, #ffffff55 50%, transparent 51%),
      radial-gradient(1px 1px at 80% 15%, #ffffff40 50%, transparent 51%),
      radial-gradient(1.5px 1.5px at 60% 60%, #ffffff35 50%, transparent 51%),
      radial-gradient(1px 1px at 30% 80%, #ffffff45 50%, transparent 51%),
      radial-gradient(1px 1px at 90% 70%, #ffffff30 50%, transparent 51%),
      radial-gradient(1.5px 1.5px at 45% 35%, #ffffff40 50%, transparent 51%);
    opacity: 0.6;
    pointer-events: none;
  }

  .hero-inner {
    position: relative;
    max-width: 760px;
    margin: 0 auto;
    display: flex;
    gap: 28px;
    align-items: flex-start;
  }

  .avatar {
    width: 110px;
    height: 110px;
    flex: none;
    border-radius: 14px;
    object-fit: cover;
    border: 2px solid var(--border-soft);
  }

  .bio p {
    margin: 0 0 16px;
    font-size: 15px;
    color: var(--text-main);
  }

  .bio p:last-child {
    margin-bottom: 0;
  }

  .interests {
    max-width: 760px;
    margin: 40px auto 0;
    padding: 0 24px;
    position: relative;
  }

  .interests h3 {
    font-size: 12px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--text-dim);
    margin: 0 0 14px;
  }

  .tags {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .tag {
    background: var(--accent-soft);
    color: #a9c6ff;
    border: 1px solid rgba(91,141,239,0.25);
    padding: 7px 14px;
    border-radius: 8px;
    font-size: 13px;
    font-weight: 500;
    white-space: nowrap;
  }

  .divider {
    height: 36px;
  }

  .education-section {
    background:
      radial-gradient(
        ellipse at 70% 0%,
        rgba(91,141,239,0.08),
        transparent 55%
      ),
      var(--bg-deep);
    padding: 56px 24px 72px;
  }

  .education-section h2,
  .section-block h2 {
    text-align: center;
    font-family: 'Playfair Display', serif;
    font-weight: 600;
    font-size: 32px;
    margin: 0 0 40px;
    color: #eef1f8;
  }

  .timeline {
    max-width: 760px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 18px;
  }

  .edu-card {
    background: var(--bg-card);
    border: 1px solid var(--border-soft);
    border-radius: 12px;
    padding: 20px 24px;
    display: flex;
    justify-content: space-between;
    gap: 20px;
    flex-wrap: wrap;
  }

  .edu-main {
    flex: 1;
    min-width: 220px;
  }

  .edu-school {
    font-size: 16px;
    font-weight: 600;
    color: #f0f3fa;
    margin: 0 0 4px;
  }

  .edu-degree {
    font-size: 14px;
    color: var(--text-dim);
    margin: 0;
  }

  .edu-note {
    font-size: 13px;
    color: #7c8aa8;
    margin: 8px 0 0;
    font-style: italic;
  }

  .edu-side {
    text-align: right;
    font-size: 13px;
    color: var(--text-dim);
    flex: none;
  }

  .edu-loc {
    font-weight: 500;
    color: #c3cbe0;
  }

  .edu-date {
    margin-top: 4px;
  }

  .divider-line {
    max-width: 760px;
    margin: 0 auto;
    border: none;
    border-top: 1px solid var(--border-soft);
  }

  .section-block {
    padding: 56px 24px;
  }

  .cert-list {
    max-width: 760px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 22px;
  }

  .cert-item {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    flex-wrap: wrap;
  }

  .cert-main {
    flex: 1;
    min-width: 220px;
  }

  .cert-name {
    font-size: 15px;
    font-weight: 600;
    color: var(--accent);
    margin: 0 0 6px;
  }

  .cert-desc {
    font-size: 14px;
    color: var(--text-dim);
    margin: 0;
  }

  .cert-date {
    font-size: 13px;
    color: var(--text-dim);
    flex: none;
    white-space: nowrap;
  }

  .edu-school-group {
    margin-bottom: 2px;
  }

  .edu-sub {
    margin: 14px 0 0;
    padding-top: 14px;
    border-top: 1px solid var(--border-soft);
  }

  .edu-sub:first-of-type {
    margin-top: 10px;
    padding-top: 0;
    border-top: none;
  }

  .placeholder-note {
    max-width: 760px;
    margin: 0 auto;
    font-size: 14px;
    color: var(--text-dim);
    text-align: center;
  }

  @media (max-width: 600px) {
    .hero-inner {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    .edu-card {
      flex-direction: column;
    }

    .edu-side {
      text-align: left;
    }

    .cert-item {
      flex-direction: column;
    }
  }
</style>

<p>
I am a machine learning researcher and
<a href="https://bubt.edu.bd/department/department-of-computer-science-engineering/faculty/profile/MDSHA">
Lecturer
</a>
in the Department of Computer Science and Engineering at the
<a href="https://bubt.edu.bd/">
Bangladesh University of Business and Technology (BUBT)
</a>.
I completed my M.Sc. in Information and Communication Technology at the
<a href="https://iitju.edu.bd/">
Institute of Information Technology, Jahangirnagar University
</a>.
My research interests lie at the intersection of
<strong>Federated Learning, Cyber Security, Artificial Intelligence, Machine Learning, Image Processing, and Computer Vision</strong>.
</p>

<p>
My current research focuses on developing
<strong>privacy-preserving, data-efficient, and reliable machine learning systems</strong>,
particularly for healthcare applications. As part of my M.Sc. research, I worked on federated semi-supervised learning for Parkinson's disease classification, with an emphasis on learning effectively from limited labeled data while preserving data privacy.
This research was supported by the
<a href="https://ims.ictd.gov.bd/">
ICT Division Fellowship 2025–2026
</a>,
with the project titled
<em>FEP-SSL: A Privacy-Preserving Semi-Supervised Learning Framework for Parkinson's Disease Classification</em>.
</p>

<p>
My research journey began with
<strong>computer vision and deep learning</strong>,
including work on real-time Bangla Sign Language detection and recognition using YOLOv10 and medical image analysis.
Under the supervision and guidance of
<a href="https://juniv.edu/teachers/mskaiser">
<strong>Professor Dr. M. Shamim Kaiser</strong>
</a>
at the Institute of Information Technology, Jahangirnagar University, I expanded my research toward
<strong>privacy-preserving, explainable, and data-efficient machine learning</strong>,
with a particular focus on federated learning and healthcare AI.
</p>

<p>
My research includes Cleanlab-guided uncertainty-based active learning for Parkinson's disease classification and privacy-preserving federated semi-supervised learning, addressing challenges related to limited labeled data and privacy-sensitive healthcare applications.
</p>

<p>
Alongside research, I am passionate about
<strong>teaching and mentoring students in computer science and engineering</strong>.
I have worked as a Lecturer at the
<a href="https://bubt.edu.bd/">
Bangladesh University of Business and Technology (BUBT)
</a>,
<a href="https://www.cub.edu.bd/">
Canadian University of Bangladesh (CUB)
</a>,
and
<a href="https://daffodilvarsity.edu.bd/">
Daffodil International University (DIU)
</a>.
I previously served as a Teaching Assistant and Research Assistant at
<a href="https://juniv.edu/">
Jahangirnagar University
</a>.
These experiences have allowed me to combine academic teaching with hands-on research and contribute to the development of students in areas related to computing and artificial intelligence.
</p>

<section class="education-section">
  <h2>Education</h2>
  <div class="timeline">
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school">Institute of Information Technology, Jahangirnagar University</p>
        <p class="edu-degree">M.Sc. in ICT; CGPA: 3.75/4.0</p>
        <p class="edu-note">Thesis (M.Sc.): FEP-SSL: A Privacy-Preserving Semi-Supervised Learning Framework for Parkinson's Disease Classification</p>
      </div>
      <div class="edu-side">
        <div class="edu-loc">Dhaka, Bangladesh</div>
        <div class="edu-date">Oct 2024 – Sep 2026</div>
      </div>
    </div>

    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school">Institute of Information Technology, Jahangirnagar University</p>
        <p class="edu-degree">B.Sc. in ICT; CGPA: 3.86/4.0 (4th position)</p>
        <p class="edu-note">Thesis (B.Sc.): Real-Time Bangla Sign Language Detection and Recognition Using YOLOv10</p>
      </div>
      <div class="edu-side">
        <div class="edu-loc">Dhaka, Bangladesh</div>
        <div class="edu-date">Feb 2019 – Sep 2024</div>
      </div>
    </div>

    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school edu-school-group">Sylhet Cadet College</p>

        <div class="edu-sub">
          <p class="edu-degree">Higher Secondary Certificate (HSC); (Science); GPA: 5.0/5.0</p>
        </div>
        <div class="edu-sub">
          <p class="edu-degree">Secondary School Certificate (SSC); (Science); GPA: 5.0/5.0</p>
        </div>
      </div>
      <div class="edu-side">
        <div class="edu-sub" style="border-top:none;padding-top:0;">
          <div class="edu-loc">Sylhet, Bangladesh</div>
          <div class="edu-date">April 2016 – May 2018</div>
        </div>
        <div class="edu-sub">
          <div class="edu-loc">Sylhet, Bangladesh</div>
          <div class="edu-date">Jan 2014 – April 2016</div>
        </div>
      </div>
    </div>
  </div>
</section>

<hr class="divider-line">

<section class="section-block">
  <h2>Certifications</h2>
  <div class="cert-list">
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">IBM Data Science Professional Certificate</p>
        <p class="cert-desc">Completed a 12-course specialization covering data science methodology, Python, SQL, data analysis, data visualization, machine learning, and generative AI applications. Gained hands-on experience through cloud-based labs and a final Capstone Project.</p>
      </div>
      <div class="cert-date">April 2025</div>
    </div>
  </div>
</section>

<hr class="divider-line">

<section class="section-block">
  <h2>Achievements</h2>
  <p class="placeholder-note"><!-- add your achievements here, in the same cert-item / cert-name / cert-desc structure as Certifications --></p>
</section>
