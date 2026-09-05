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
  image_circular: true
  more_info: >

selected_papers: true
social: true

# announcements:
#   enabled: true
#   scrollable: true
#   limit: 5

# latest_posts:
#   enabled: true
#   scrollable: true
#   limit: 3
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
    border: true;
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
  /* ==================== RESEARCH INTERESTS ==================== */

.research-interests {
  max-width: 760px;
  margin: 40px auto 0;
  padding: 28px 0 0;
  border-top: 1px solid var(--border-soft);
}

.research-interests h2 {
  font-family: 'Inter', system-ui, sans-serif;
  font-size: 17px;
  font-weight: 700;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  color: #eef1f8;
  margin: 0 0 16px;
}

.interest-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.interest-tag {
  display: inline-flex;
  align-items: center;
  padding: 8px 13px;
  border-radius: 18px;
  background: rgba(91, 141, 239, 0.10);
  border: 1px solid rgba(255, 255, 255, 0.14);
  color: #dce5f5;
  font-size: 13px;
  font-weight: 500;
  line-height: 1.2;
  white-space: nowrap;
  transition: all 0.2s ease;
}

.interest-tag:hover {
  background: rgba(91, 141, 239, 0.18);
  border-color: rgba(91, 141, 239, 0.35);
  color: #ffffff;
}

@media (max-width: 600px) {
  .research-interests {
    margin-top: 32px;
    padding: 24px 0 0;
  }

  .research-interests h2 {
    font-size: 16px;
  }

  .interest-tags {
    gap: 8px;
  }

  .interest-tag {
    font-size: 12px;
    padding: 7px 11px;
  }
}

/* =========================================================
   TECHNICAL SKILLS
   ========================================================= */

.skills-list {

  display: grid;

  grid-template-columns: repeat(2, 1fr);

  gap: 18px;
}

.skill-item {

  background: var(--portfolio-card);

  border: 1px solid var(--portfolio-border);

  border-radius: 10px;

  padding: 22px;

  transition: all 0.25s ease;
}

.skill-item:hover {

  background: var(--portfolio-card-hover);

  transform: translateY(-2px);
}

.skill-name {

  margin: 0 0 10px;

  color: var(--portfolio-accent);

  font-weight: 700;

  font-size: 1rem;
}

.skill-desc {

  margin: 0;

  color: var(--portfolio-muted);

  line-height: 1.7;

  font-size: 0.88rem;
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


<hr class="divider-line">
<!-- ==================== RESEARCH INTERESTS ==================== -->

<section class="research-interests">

  <h2>Research Interests</h2>

  <div class="interest-tags">

    <span class="interest-tag">
      Federated Learning
    </span>

    <span class="interest-tag">
      Cyber Security
    </span>

    <span class="interest-tag">
      Privacy Privacy
    </span>

    <span class="interest-tag">
      Artificial Intelligence
    </span>

    <span class="interest-tag">
      Semi-supervised Learning
    </span>

    <span class="interest-tag">
      Machine Learning
    </span>

    <span class="interest-tag">
      Image Processing
    </span>

    <span class="interest-tag">
      Computer Vision
    </span>


  </div>

</section>


<hr class="divider-line">
<section class="education-section">
  <h2>Education</h2>

  <div class="timeline">

    <!-- M.Sc. -->
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school">
          Institute of Information Technology, Jahangirnagar University
        </p>

        <a href="https://drive.google.com/file/d/16aIfdCM5Bt0XjIWH47rDqLdmt9idpkE6/view?usp=drive_link"
           target="_blank"
           rel="noopener noreferrer">
          <p class="edu-degree">
            M.Sc. in ICT; CGPA: 3.75/4.0
          </p>
        </a>

        <p class="edu-note">
          Thesis (M.Sc.): FEP-SSL: A Privacy-Preserving Semi-Supervised
          Learning Framework for Parkinson's Disease Classification
        </p>
      </div>

      <div class="edu-side">
        <div class="edu-loc">Dhaka, Bangladesh</div>
        <div class="edu-date">Oct 2024 – Sep 2026</div>
      </div>
    </div>


    <!-- B.Sc. -->
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school">
          Institute of Information Technology, Jahangirnagar University
        </p>

        <a href="https://drive.google.com/file/d/1NFqiSCK6Hg0eh4tgNG9K6_tdsR3Nj4PQ/view?usp=sharing"
           target="_blank"
           rel="noopener noreferrer">
          <p class="edu-degree">
            B.Sc. in ICT; CGPA: 3.86/4.0 (4th position)
          </p>
        </a>

        <p class="edu-note">
          Thesis (B.Sc.): Real-Time Bangla Sign Language Detection and
          Recognition Using YOLOv10
        </p>
      </div>

      <div class="edu-side">
        <div class="edu-loc">Dhaka, Bangladesh</div>
        <div class="edu-date">Feb 2019 – Sep 2024</div>
      </div>
    </div>


    <!-- HSC -->
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school edu-school-group">
          Dinajpur Govt. College
        </p>

        <div class="edu-sub">
          <a href="https://drive.google.com/file/d/1T-4sbylCgV18rKrN6SyuCOFDP0s2rs72/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            <p class="edu-degree">
              Higher Secondary Certificate (HSC); Science; GPA: 5.0/5.0
            </p>
          </a>
        </div>
      </div>

      <div class="edu-side">
        <div class="edu-loc">Dinajpur, Bangladesh</div>
        <div class="edu-date">2016 – 2018</div>
      </div>
    </div>


    <!-- SSC -->
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school edu-school-group">
          Panchkur B\L High School
        </p>

        <div class="edu-sub">
          <a href="https://drive.google.com/file/d/1osWGSHjY9RAbxn_ifhFAzW8Vd_ujt1VT/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            <p class="edu-degree">
              Secondary School Certificate (SSC); Science; GPA: 5.0/5.0
            </p>
          </a>
        </div>
      </div>

      <div class="edu-side">
        <div class="edu-loc">Dinajpur, Bangladesh</div>
        <div class="edu-date">2014 – 2016</div>
      </div>
    </div>

  </div>
</section>


<hr class="divider-line">

<!-- ==================== HONORS AND AWARDS ==================== -->

<section class="section-block">
  <h2>Honors and Awards</h2>

  <div class="cert-list">

    <!-- ICT Division Fellowship -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/1lCtDA3zSwH3vj1NPrKfoYh6sfrPSHMLz/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            Information and Communication Technology (ICT) Division Fellowship
          </a>
        </p>

        <p class="cert-desc">
          Awarded the ICT Division Fellowship for the 2025–2026 academic
          session for research on
          <em>“FEP-SSL: A Privacy-Preserving Semi-Supervised Learning
          Framework for Parkinson’s Disease Classification.”</em>
        </p>
      </div>

      <div class="cert-date">
        2025 – 2026
      </div>
    </div>


    <!-- NST Fellowship -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/1ukv5D60qS6wI1gxfXyz6FpkMQ_HyA47a/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            National Science and Technology (NST) Fellowship
          </a>
        </p>

        <p class="cert-desc">
          Awarded the National Science and Technology (NST) Fellowship
          for the 2025–2026 academic session for research on
          <em>“Privacy-Preserving Federated Semi-Supervised Learning
          Model for Healthcare Applications.”</em>
        </p>
      </div>

      <div class="cert-date">
        2025 – 2026
      </div>
    </div>


    <!-- University Merit Scholarship -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://juniv.edu/"
             target="_blank"
             rel="noopener noreferrer">
            University Merit Scholarship
          </a>
        </p>

        <p class="cert-desc">
          Awarded a university merit scholarship for outstanding
          academic performance in the B.Sc. (Hons.) in ICT program,
          covering academic results from Part I to Part VIII at the
          Institute of Information Technology, Jahangirnagar University.
        </p>
      </div>

      <div class="cert-date">
        2019 – 2024
      </div>
    </div>


    <!-- IEEEXtreme -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_IEEEXTREME_LINK"
             target="_blank"
             rel="noopener noreferrer">
            IEEEXtreme 14.0 Programming Contest
          </a>
        </p>

        <p class="cert-desc">
          Participated in the IEEEXtreme 14.0 programming contest
          organized by IEEE in 2021. My team,
          <em>“JUinception,”</em> ranked
          <strong>498th out of 2,155 teams worldwide</strong> and secured
          <strong>11th position in Bangladesh</strong>.
        </p>
      </div>

      <div class="cert-date">
        2021
      </div>
    </div>


    <!-- Dementia Workshop -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_DEMENTIA_WORKSHOP_LINK"
             target="_blank"
             rel="noopener noreferrer">
            Workshop on Early Detection and Management of Dementia
            using Explainable Artificial Intelligence
          </a>
        </p>

        <p class="cert-desc">
          Participating member in the workshop
          <em>“Early Detection and Management of Dementia using
          Explainable Artificial Intelligence,”</em> awarded by
          Nottingham Trent University, England.
        </p>
      </div>
    </div>


    <!-- Debate Finalist -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_DEBATE_FINALIST_LINK"
             target="_blank"
             rel="noopener noreferrer">
            Debate Finalist
          </a>
        </p>

        <p class="cert-desc">
          Achieved finalist status in a debate competition organized
          by the Dinajpur Debating Society.
        </p>
      </div>
    </div>

  </div>
</section>

<hr class="divider-line">

<!-- ==================== CERTIFICATIONS ==================== -->

<section class="section-block">
  <h2>Certifications</h2>

  <div class="cert-list">




    <!-- Cyber Security -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/18KFyvAjJjQBL97XDjT1hrtb7TMxXRUox/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            Cyber Security
          </a>
        </p>

        <p class="cert-desc">
          Enhancing Digital Government and Economy (EDGE)
        </p>
      </div>

      <div class="cert-date">
        Sep 2024 – Dec 2024
      </div>
    </div>


    <!-- Software Testing -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/11vjOE41rv4mdr7RnSify30t_IFvAoasW/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            Software Testing
          </a>
        </p>

        <p class="cert-desc">
          Enhancing Digital Government and Economy (EDGE)
        </p>
      </div>

      <div class="cert-date">
        Mar 2024 – May 2024
      </div>
    </div>


    <!-- Graphics Design -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/1rtKzPKqB0tIe2WjNwa8EPyC13nkH3i6l/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            Graphics Design
          </a>
        </p>

        <p class="cert-desc">
          Learning &amp; Earning Development Project (LEDP)
        </p>
      </div>

      <div class="cert-date">
        Jan 2020 – Jun 2020
      </div>
    </div>


    <!-- Youth Social Leadership -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/1Ae6YWbL-Wy5OZon2pUjOYipNHDjWJpxl/view"
             target="_blank"
             rel="noopener noreferrer">
            Youth Social Leadership
          </a>
        </p>

        <p class="cert-desc">
          Bangladesh Youth Leadership Training
        </p>
      </div>

      <div class="cert-date">
        Feb 2020 – Mar 2020
      </div>
    </div>

  </div>
</section>


<hr class="divider-line">

<!-- ==================== CO-CURRICULAR ACTIVITIES ==================== -->

<section class="section-block">
  <h2>Co-Curricular Activities and Services</h2>

  <div class="cert-list">

    <!-- Admission Helpline -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_ADMISSION_HELPLINE_LINK"
             target="_blank"
             rel="noopener noreferrer">
            Admission Helpline Assistant
          </a>
        </p>

        <p class="cert-desc">
          Assisted students and applicants through the
          Jahangirnagar University Admission Helpline.
        </p>
      </div>

      <div class="cert-date">
        2023 – 2024
      </div>
    </div>


    <!-- General Secretary -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_DINAJPUR_STUDENTS_ASSOCIATION_LINK"
             target="_blank"
             rel="noopener noreferrer">
            General Secretary
          </a>
        </p>

        <p class="cert-desc">
          Dinajpur Students Association of Jahangirnagar University.
          Served as General Secretary and contributed to organizational,
          student-support, and social activities.
        </p>
      </div>

      <div class="cert-date">
        2022 – 2025
      </div>
    </div>


    <!-- Science Club -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_JU_SCIENCE_CLUB_LINK"
             target="_blank"
             rel="noopener noreferrer">
            General Member
          </a>
        </p>

        <p class="cert-desc">
          Jahangirnagar University Science Club.
        </p>
      </div>

      <div class="cert-date">
        2019 – 2022
      </div>
    </div>


    <!-- Savar Half Marathon -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_SAVAR_HALF_MARATHON_LINK"
             target="_blank"
             rel="noopener noreferrer">
            Volunteer
          </a>
        </p>

        <p class="cert-desc">
          Volunteer at the Savar Half Marathon, contributing to
          event organization and participant support.
        </p>
      </div>

      <div class="cert-date">
        2022
      </div>
    </div>

  </div>
</section>


<hr class="divider-line">
<!-- ========================================================= -->
<!-- TECHNICAL SKILLS -->
<!-- ========================================================= -->

<section class="section-block">

<h2>Technical Skills</h2>

<div class="skills-list">


<div class="skill-item">

<p class="skill-name">
Languages
</p>

<p class="skill-desc">
C, C++, Java, Python, PHP, LaTeX, HTML, CSS, JavaScript, MySQL
</p>

</div>


<div class="skill-item">

<p class="skill-name">
Machine Learning
</p>

<p class="skill-desc">
PyTorch, Keras, OpenCV, TensorFlow, NLTK, Pandas, NumPy, Matplotlib
</p>

</div>


<div class="skill-item">

<p class="skill-name">
Developer Tools
</p>

<p class="skill-desc">
Visual Studio Code, Code::Blocks, LaTeX, PyCharm,
Jupyter Notebook, Eclipse
</p>

</div>


<div class="skill-item">

<p class="skill-name">
Illustration Tools
</p>

<p class="skill-desc">
Adobe Illustrator, Adobe Photoshop, Canva,
Adobe Animate, Adobe Premiere Pro
</p>

</div>


</div>

</section>

<hr class="divider-line">
<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2026 Md. Shakil Ahmed. All rights reserved.
    </p>
  </div>
</footer>