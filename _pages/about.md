---
layout: about
title: Profile
permalink: /

subtitle: >
  <a href="https://bubt.edu.bd/department/department-of-computer-science-engineering/faculty/profile/MDSHA">
  Lecturer</a>, Department of Computer Science and Engineering,
  Bangladesh University of Business and Technology

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false
  more_info: ""

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>

/* =========================================================
   PROFILE / HOME PAGE DESIGN
   ========================================================= */

:root {
  --portfolio-bg: #0b1120;
  --portfolio-panel: #111a2e;
  --portfolio-card: #16213a;
  --portfolio-card-hover: #1a2845;

  --portfolio-border: rgba(255, 255, 255, 0.10);

  --portfolio-text: #e6ebf5;
  --portfolio-muted: #9aa6bd;

  --portfolio-accent: #5b8def;
  --portfolio-accent-light: #9ab8ff;

  --portfolio-shadow: 0 10px 35px rgba(0, 0, 0, 0.20);
}


/* =========================================================
   ABOUT PAGE
   ========================================================= */

.post {
  color: var(--portfolio-text);
}

.post p {
  line-height: 1.8;
}


/* =========================================================
   PROFILE IMAGE
   ========================================================= */

.profile {
  margin-right: 28px !important;
  margin-bottom: 20px !important;
}

.profile img {
  border-radius: 10px !important;
  border: 1px solid var(--portfolio-border);
  box-shadow: var(--portfolio-shadow);
}


/* =========================================================
   LINKS
   ========================================================= */

.post a {
  color: var(--portfolio-accent);
  text-decoration: none;
}

.post a:hover {
  color: var(--portfolio-accent-light);
  text-decoration: none;
}


/* =========================================================
   SECTION WRAPPER
   ========================================================= */

.portfolio-section {
  max-width: 850px;
  margin: 70px auto;
  padding: 0 15px;
}

.portfolio-section h2 {
  text-align: center;
  margin-bottom: 40px;
  font-size: 2rem;
  font-weight: 700;
  color: var(--portfolio-text);
}


/* =========================================================
   RESEARCH INTERESTS
   ========================================================= */

.research-interests {
  max-width: 850px;
  margin: 45px auto 70px;
  padding: 30px 0;
  border-top: 1px solid var(--portfolio-border);
}

.research-interests h2 {
  text-align: left;
  font-size: 1rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  margin-bottom: 20px;
  color: var(--portfolio-text);
}

.interest-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.interest-tag {
  padding: 8px 15px;

  border-radius: 20px;

  background: rgba(91, 141, 239, 0.10);

  border: 1px solid rgba(91, 141, 239, 0.25);

  color: var(--portfolio-accent-light);

  font-size: 0.82rem;

  transition: all 0.25s ease;
}

.interest-tag:hover {
  background: rgba(91, 141, 239, 0.20);
  border-color: var(--portfolio-accent);
  color: #ffffff;
}


/* =========================================================
   EDUCATION CARDS
   ========================================================= */

.education-section {
  max-width: 850px;
  margin: 80px auto;
}

.education-section h2 {
  text-align: center;
  margin-bottom: 40px;
}

.timeline {
  display: flex;
  flex-direction: column;
  gap: 18px;
}

.edu-card {

  background: var(--portfolio-card);

  border: 1px solid var(--portfolio-border);

  border-radius: 12px;

  padding: 22px 25px;

  display: flex;

  justify-content: space-between;

  gap: 25px;

  transition: all 0.25s ease;
}

.edu-card:hover {
  background: var(--portfolio-card-hover);
  transform: translateY(-2px);
}

.edu-main {
  flex: 1;
}

.edu-school {

  margin: 0 0 6px;

  font-size: 1rem;

  font-weight: 650;

  color: var(--portfolio-text);
}

.edu-degree {

  margin: 0;

  color: var(--portfolio-muted);

  font-size: 0.9rem;
}

.edu-note {

  margin: 10px 0 0;

  color: #7f8ca5;

  font-size: 0.82rem;

  font-style: italic;
}

.edu-side {

  min-width: 150px;

  text-align: right;

  font-size: 0.82rem;

  color: var(--portfolio-muted);
}

.edu-loc {
  font-weight: 600;
  color: #c9d3e6;
}

.edu-date {
  margin-top: 5px;
}


/* =========================================================
   LIST SECTIONS
   ========================================================= */

.section-block {

  max-width: 850px;

  margin: 85px auto;
}

.section-block h2 {

  text-align: center;

  margin-bottom: 40px;

  color: var(--portfolio-text);
}

.cert-list {

  display: flex;

  flex-direction: column;

  gap: 25px;
}

.cert-item {

  padding: 20px 22px;

  background: var(--portfolio-card);

  border: 1px solid var(--portfolio-border);

  border-radius: 10px;

  display: flex;

  justify-content: space-between;

  gap: 25px;

  transition: all 0.25s ease;
}

.cert-item:hover {

  background: var(--portfolio-card-hover);

  transform: translateY(-2px);
}

.cert-main {
  flex: 1;
}

.cert-name {

  margin: 0 0 8px;

  font-size: 1rem;

  font-weight: 650;
}

.cert-desc {

  margin: 0;

  color: var(--portfolio-muted);

  font-size: 0.88rem;

  line-height: 1.7;
}

.cert-date {

  min-width: 120px;

  text-align: right;

  font-size: 0.8rem;

  color: var(--portfolio-muted);
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


/* =========================================================
   DIVIDER
   ========================================================= */

.divider-line {

  max-width: 850px;

  margin: 70px auto;

  border: none;

  border-top: 1px solid var(--portfolio-border);
}


/* =========================================================
   MOBILE
   ========================================================= */

@media (max-width: 768px) {

  .profile {
    float: none !important;
    margin: 0 auto 25px !important;
    text-align: center;
  }

  .edu-card,
  .cert-item {
    flex-direction: column;
  }

  .edu-side,
  .cert-date {
    text-align: left;
  }

  .skills-list {
    grid-template-columns: 1fr;
  }

}

</style>


<!-- ========================================================= -->
<!-- BIO -->
<!-- ========================================================= -->

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
<strong>Federated Learning, Cyber Security, Artificial Intelligence,
Machine Learning, Image Processing, and Computer Vision.</strong>
</p>


<p>
My current research focuses on developing
<strong>privacy-preserving, data-efficient, and reliable machine learning systems</strong>,
particularly for healthcare applications. As part of my M.Sc. research, I worked
on federated semi-supervised learning for Parkinson's disease classification,
with an emphasis on learning effectively from limited labeled data while
preserving data privacy.
</p>


<p>
This research was supported by the
<a href="https://ims.ictd.gov.bd/">
ICT Division Fellowship 2025–2026
</a>,
with the project titled
<em>FEP-SSL: A Privacy-Preserving Semi-Supervised Learning Framework
for Parkinson's Disease Classification</em>.
</p>


<p>
My research journey began with
<strong>computer vision and deep learning</strong>,
including work on real-time Bangla Sign Language detection and recognition using
YOLOv10 and medical image analysis. Under the supervision and guidance of
<a href="https://juniv.edu/teachers/mskaiser">
<strong>Professor Dr. M. Shamim Kaiser</strong>
</a>,
I expanded my research toward privacy-preserving, explainable, and
data-efficient machine learning.
</p>


<p>
Alongside research, I am passionate about
<strong>teaching and mentoring students in computer science and engineering.</strong>
I have worked at the Bangladesh University of Business and Technology,
Canadian University of Bangladesh, and Daffodil International University.
</p>


<!-- ========================================================= -->
<!-- RESEARCH INTERESTS -->
<!-- ========================================================= -->

<section class="research-interests">

<h2>Research Interests</h2>

<div class="interest-tags">

<span class="interest-tag">Federated Learning</span>

<span class="interest-tag">Cyber Security</span>

<span class="interest-tag">Privacy-Preserving AI</span>

<span class="interest-tag">Artificial Intelligence</span>

<span class="interest-tag">Semi-Supervised Learning</span>

<span class="interest-tag">Machine Learning</span>

<span class="interest-tag">Image Processing</span>

<span class="interest-tag">Computer Vision</span>

</div>

</section>


<!-- ========================================================= -->
<!-- EDUCATION -->
<!-- ========================================================= -->

<section class="education-section">

<h2>Education</h2>

<div class="timeline">


<div class="edu-card">

<div class="edu-main">

<p class="edu-school">
Institute of Information Technology, Jahangirnagar University
</p>

<p class="edu-degree">
<a href="https://drive.google.com/file/d/16aIfdCM5Bt0XjIWH47rDqLdmt9idpkE6/view?usp=drive_link">
M.Sc. in ICT; CGPA: 3.75/4.0
</a>
</p>

<p class="edu-note">
Thesis: FEP-SSL: A Privacy-Preserving Semi-Supervised Learning Framework
for Parkinson's Disease Classification
</p>

</div>

<div class="edu-side">

<div class="edu-loc">Dhaka, Bangladesh</div>

<div class="edu-date">Oct 2024 – Sep 2026</div>

</div>

</div>


<div class="edu-card">

<div class="edu-main">

<p class="edu-school">
Institute of Information Technology, Jahangirnagar University
</p>

<p class="edu-degree">
<a href="https://drive.google.com/file/d/1NFqiSCK6Hg0eh4tgNG9K6_tdsR3Nj4PQ/view?usp=sharing">
B.Sc. in ICT; CGPA: 3.86/4.0 (4th Position)
</a>
</p>

<p class="edu-note">
Thesis: Real-Time Bangla Sign Language Detection and Recognition Using YOLOv10
</p>

</div>

<div class="edu-side">

<div class="edu-loc">Dhaka, Bangladesh</div>

<div class="edu-date">Feb 2019 – Sep 2024</div>

</div>

</div>


<div class="edu-card">

<div class="edu-main">

<p class="edu-school">
Dinajpur Govt. College
</p>

<p class="edu-degree">
Higher Secondary Certificate (HSC); Science; GPA: 5.0/5.0
</p>

</div>

<div class="edu-side">

<div class="edu-loc">Dinajpur, Bangladesh</div>

<div class="edu-date">2016 – 2018</div>

</div>

</div>


<div class="edu-card">

<div class="edu-main">

<p class="edu-school">
Panchkur B/L High School
</p>

<p class="edu-degree">
Secondary School Certificate (SSC); Science; GPA: 5.0/5.0
</p>

</div>

<div class="edu-side">

<div class="edu-loc">Dinajpur, Bangladesh</div>

<div class="edu-date">2014 – 2016</div>

</div>

</div>


</div>

</section>


<!-- ========================================================= -->
<!-- HONORS AND AWARDS -->
<!-- ========================================================= -->

<section class="section-block">

<h2>Honors and Awards</h2>

<div class="cert-list">


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
<a href="https://drive.google.com/file/d/1lCtDA3zSwH3vj1NPrKfoYh6sfrPSHMLz/view?usp=drive_link">
ICT Division Fellowship
</a>
</p>

<p class="cert-desc">
Awarded the ICT Division Fellowship for the 2025–2026 academic session
for research on FEP-SSL, a privacy-preserving semi-supervised learning
framework for Parkinson's disease classification.
</p>

</div>

<div class="cert-date">
2025 – 2026
</div>

</div>


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
<a href="https://drive.google.com/file/d/1ukv5D60qS6wI1gxfXyz6FpkMQ_HyA47a/view?usp=drive_link">
National Science and Technology (NST) Fellowship
</a>
</p>

<p class="cert-desc">
Awarded for research on privacy-preserving federated semi-supervised
learning for healthcare applications.
</p>

</div>

<div class="cert-date">
2025 – 2026
</div>

</div>


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
University Merit Scholarship
</p>

<p class="cert-desc">
Awarded for outstanding academic performance throughout the B.Sc. (Hons.)
in ICT program at Jahangirnagar University.
</p>

</div>

<div class="cert-date">
2019 – 2024
</div>

</div>


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
IEEEXtreme 14.0 Programming Contest
</p>

<p class="cert-desc">
Ranked 498th among 2,155 teams worldwide and secured 11th position in Bangladesh.
</p>

</div>

<div class="cert-date">
2021
</div>

</div>


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
Workshop on Early Detection and Management of Dementia using Explainable AI
</p>

<p class="cert-desc">
Participating member in a workshop awarded by Nottingham Trent University,
England.
</p>

</div>

</div>


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
Debate Finalist
</p>

<p class="cert-desc">
Achieved finalist status in a debate competition organized by the
Dinajpur Debating Society.
</p>

</div>

</div>


</div>

</section>


<!-- ========================================================= -->
<!-- CERTIFICATIONS -->
<!-- ========================================================= -->

<section class="section-block">

<h2>Certifications</h2>

<div class="cert-list">


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
<a href="https://drive.google.com/file/d/18KFyvAjJjQBL97XDjT1hrtb7TMxXRUox/view?usp=drive_link">
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


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
<a href="https://drive.google.com/file/d/11vjOE41rv4mdr7RnSify30t_IFvAoasW/view?usp=drive_link">
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


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
<a href="https://drive.google.com/file/d/1rtKzPKqB0tIe2WjNwa8EPyC13nkH3i6l/view?usp=drive_link">
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


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
Youth Social Leadership
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


<!-- ========================================================= -->
<!-- CO-CURRICULAR -->
<!-- ========================================================= -->

<section class="section-block">

<h2>Co-Curricular Activities and Services</h2>

<div class="cert-list">


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
Admission Helpline Assistant
</p>

<p class="cert-desc">
Assisted students and applicants through the Jahangirnagar University
Admission Helpline.
</p>

</div>

<div class="cert-date">
2023 – 2024
</div>

</div>


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
General Secretary
</p>

<p class="cert-desc">
Dinajpur Students Association of Jahangirnagar University.
Contributed to organizational, student-support, and social activities.
</p>

</div>

<div class="cert-date">
2022 – 2025
</div>

</div>


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
General Member
</p>

<p class="cert-desc">
Jahangirnagar University Science Club.
</p>

</div>

<div class="cert-date">
2019 – 2022
</div>

</div>


<div class="cert-item">

<div class="cert-main">

<p class="cert-name">
Volunteer
</p>

<p class="cert-desc">
Volunteer at the Savar Half Marathon, contributing to event organization
and participant support.
</p>

</div>

<div class="cert-date">
2022
</div>

</div>


</div>

</section>


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