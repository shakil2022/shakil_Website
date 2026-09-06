---
layout: page
title: Bangladeshi Sign Language Detection
description: A YOLOv10-based system for recognizing static Bangladeshi Sign Language gestures and translating them into text.
img: assets/img/sign-language-detection.jpg
importance: 2
category: work
related_publications: false
---
<style>
.project-card {
  position: relative;
  padding: 28px 30px;
  margin: 20px 0 35px 0;
  border: 1px solid rgba(255, 255, 255, 0.15);
  border-radius: 18px;
  background: linear-gradient(
    135deg,
    rgba(38, 65, 105, 0.95),
    rgba(25, 48, 82, 0.95)
  );
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
  color: #ffffff;
}

.project-header {
  display: flex;
  align-items: center;
  gap: 14px;
  margin-bottom: 18px;
}

.project-icon {
  width: 58px;
  height: 72px;
  border: 1px solid rgba(180, 200, 240, 0.8);
  border-radius: 14px;
  background: rgba(35, 65, 100, 0.8);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 30px;
  flex-shrink: 0;
}

.project-title {
  margin: 0 !important;
  font-size: 22px;
  font-weight: 700;
  color: #ffffff !important;
}

.project-subtitle {
  margin: 5px 0 0 0;
  font-size: 15px;
  font-weight: 500;
  color: #dce5f5;
}

.project-description {
  margin-top: 18px;
  font-size: 15px;
  line-height: 1.65;
  color: #e8edf7;
  text-align: justify;
  text-justify: inter-word;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 18px;
}

.project-tag {
  display: inline-block;
  padding: 6px 11px;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.12);
  border: 1px solid rgba(255, 255, 255, 0.15);
  color: #eef3fc;
  font-size: 12px;
  font-weight: 500;
}

.project-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 20px;
}

.project-button {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 9px 16px;
  border-radius: 8px;
  border: 1px solid rgba(255, 255, 255, 0.18);
  text-decoration: none !important;
  font-size: 13px;
  font-weight: 600;
  transition: all 0.2s ease;
}

.project-button.primary {
  background: #aebce8;
  color: #172746 !important;
}

.project-button.secondary {
  background: transparent;
  color: #e8edf7 !important;
}

.project-button:hover {
  transform: translateY(-2px);
  text-decoration: none !important;
}

.project-button.primary:hover {
  background: #c2cdf0;
}

.project-button.secondary:hover {
  background: rgba(255, 255, 255, 0.08);
}

.project-content {
  margin-top: 35px;
}

.project-section-title {
  font-size: 22px;
  font-weight: 700;
  margin-top: 30px;
  margin-bottom: 15px;
}

.project-content p {
  text-align: justify;
  text-justify: inter-word;
  line-height: 1.7;
}

@media (max-width: 576px) {
  .project-card {
    padding: 20px;
  }

  .project-title {
    font-size: 19px;
  }

  .project-description {
    font-size: 14px;
  }

  .project-icon {
    width: 50px;
    height: 62px;
    font-size: 25px;
  }
}
</style>
<div class="project-card">

  <div class="project-header">

    <div class="project-icon">
      <i class="fas fa-hands"></i>
    </div>

    <div>
      <h1 class="project-title">
        Bangladeshi Sign Language Detection
      </h1>

      <p class="project-subtitle">
        A YOLOv10-based system for recognizing static Bangladeshi Sign Language
        gestures and translating them into text.
      </p>
    </div>

  </div>

  <div class="project-description">

    Developed a <strong>Bangladeshi Sign Language (BdSL) Detection System</strong>
    to help bridge communication barriers faced by deaf and mute individuals.
    The system recognizes static Bangladeshi Sign Language hand gestures and
    translates them into text, supporting more inclusive and accessible
    communication.

    The proposed approach leverages <strong>YOLOv10</strong>, a
    state-of-the-art object detection model, trained on a custom dataset of
    labeled BdSL gesture images. The model was designed to provide accurate
    and efficient recognition of <strong>14 unique static signs</strong>.

  </div>

  <div class="project-tags">
    <span class="project-tag">YOLOv10</span>
    <span class="project-tag">Python</span>
    <span class="project-tag">Computer Vision</span>
    <span class="project-tag">Deep Learning</span>
    <span class="project-tag">Object Detection</span>
    <span class="project-tag">Sign Language Recognition</span>
    <span class="project-tag">Bangladeshi Sign Language</span>
    <span class="project-tag">14 Static Signs</span>
    <span class="project-tag">Custom Dataset</span>
    <span class="project-tag">Text Translation</span>
  </div>

  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/SIGN_LANGUAGE_DETECTION"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      View Code
    </a>

  </div>

</div>

<div class="project-content">

  <h2 class="project-section-title">
    Project Overview
  </h2>

  <p>
    There is a critical need for accurate Bangladeshi Sign Language (BdSL)
    detection systems to create a more inclusive environment for people who
    are deaf and mute. Communication barriers can contribute to social
    isolation and limit access to education, services, and everyday
    interactions.
  </p>

  <p>
    This project proposes a computer vision-based system that recognizes
    Bangladeshi Sign Language hand gestures and translates them into text.
    By facilitating communication between sign language users and others,
    the system aims to reduce communication barriers and support greater
    social inclusion.
  </p>

  <p>
    The proposed method uses <strong>YOLOv10</strong>, a state-of-the-art
    object detection model, to achieve accurate and efficient BdSL gesture
    recognition. A custom dataset of <strong>1,949 labeled images</strong>
    covering <strong>14 unique static signs</strong> was used to train and
    evaluate the model.
  </p>

  <h2 class="project-section-title">
    Methodology
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-database"></i>
            Custom Dataset
          </h4>

          <p class="card-text">
            A curated dataset of 1,949 labeled images representing
            14 unique static Bangladeshi Sign Language gestures.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-brain"></i>
            YOLOv10 Model
          </h4>

          <p class="card-text">
            A custom YOLOv10 object detection model trained to identify
            and recognize static BdSL hand gestures.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-cogs"></i>
            Model Training
          </h4>

          <p class="card-text">
            The model was trained on labeled gesture images to improve
            recognition accuracy and robustness across the selected signs.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-language"></i>
            Text Translation
          </h4>

          <p class="card-text">
            Recognized hand gestures are translated into text to support
            communication between sign language users and others.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    System Workflow
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-camera"></i>
            1. Input Image
          </h4>

          <p class="card-text">
            A hand gesture image is provided as input to the detection system.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-search"></i>
            2. Gesture Detection
          </h4>

          <p class="card-text">
            The trained YOLOv10 model detects the hand gesture and identifies
            the corresponding sign class.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-check-circle"></i>
            3. Sign Recognition
          </h4>

          <p class="card-text">
            The detected gesture is classified into one of the 14 supported
            Bangladeshi Sign Language signs.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-comment-alt"></i>
            4. Text Output
          </h4>

          <p class="card-text">
            The recognized sign is converted into text to facilitate
            communication.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    Dataset and Model Details
  </h2>

  <div class="table-responsive">

    <table class="table table-bordered">

      <thead>
        <tr>
          <th>Attribute</th>
          <th>Details</th>
        </tr>
      </thead>

      <tbody>

        <tr>
          <td>Project Type</td>
          <td>Computer Vision and Sign Language Recognition</td>
        </tr>

        <tr>
          <td>Model</td>
          <td>YOLOv10</td>
        </tr>

        <tr>
          <td>Dataset</td>
          <td>Custom labeled Bangladeshi Sign Language dataset</td>
        </tr>

        <tr>
          <td>Total Images</td>
          <td>1,949</td>
        </tr>

        <tr>
          <td>Number of Signs</td>
          <td>14 unique static signs</td>
        </tr>

        <tr>
          <td>Recognition Type</td>
          <td>Static hand gesture detection</td>
        </tr>

        <tr>
          <td>Output</td>
          <td>Recognized sign translated into text</td>
        </tr>

        <tr>
          <td>Primary Objective</td>
          <td>Bridging communication barriers through BdSL recognition</td>
        </tr>

      </tbody>

    </table>

  </div>

  <h2 class="project-section-title">
    Performance Results
  </h2>

  <p>
    The proposed method was evaluated on the custom dataset containing
    1,949 images of 14 unique signs. The model achieved the following
    performance across all classes.
  </p>

  <div class="table-responsive">

    <table class="table table-bordered">

      <thead>
        <tr>
          <th>Metric</th>
          <th>Performance</th>
        </tr>
      </thead>

      <tbody>

        <tr>
          <td>F1-Confidence Rate</td>
          <td>86%</td>
        </tr>

        <tr>
          <td>Recall-Confidence Rate</td>
          <td>98%</td>
        </tr>

        <tr>
          <td>Precision-Confidence Rate</td>
          <td>100%</td>
        </tr>

        <tr>
          <td>Precision-Recall Rate</td>
          <td>90.3%</td>
        </tr>

        <tr>
          <td>Overall Average Accuracy</td>
          <td>90.67%</td>
        </tr>

      </tbody>

    </table>

  </div>

  <h2 class="project-section-title">
    Key Contributions
  </h2>

  <ul>

    <li>
      <strong>Inclusive Communication:</strong>
      Develops a system intended to reduce communication barriers faced by
      deaf and mute individuals.
    </li>

    <li>
      <strong>YOLOv10-Based Detection:</strong>
      Applies a state-of-the-art object detection model to Bangladeshi
      Sign Language recognition.
    </li>

    <li>
      <strong>Custom Dataset:</strong>
      Uses a curated dataset of 1,949 labeled images covering 14 unique
      static signs.
    </li>

    <li>
      <strong>Accurate Recognition:</strong>
      Achieves an overall average accuracy of 90.67% across the supported
      signs.
    </li>

    <li>
      <strong>Practical Application:</strong>
      Provides a foundation for developing accessible sign language
      communication tools.
    </li>

  </ul>

  <h2 class="project-section-title">
    Social Impact
  </h2>

  <p>
    This project aims to contribute to a more inclusive society by
    addressing communication barriers faced by people who rely on
    Bangladeshi Sign Language. By translating hand gestures into text,
    the system has the potential to improve everyday communication,
    reduce social isolation, and support greater participation in
    education, employment, and community activities.
  </p>

  <p>
    The research also contributes to the development of sign language
    recognition technology and provides a foundation for future systems
    capable of supporting a wider range of gestures and real-time
    communication scenarios.
  </p>

  <h2 class="project-section-title">
    Future Improvements
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-video"></i>
            Real-Time Recognition
          </h4>

          <p class="card-text">
            Extend the system to support real-time gesture recognition
            through video input and live camera streams.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-expand-arrows-alt"></i>
            Expanded Sign Vocabulary
          </h4>

          <p class="card-text">
            Increase the number of supported signs to improve the coverage
            of Bangladeshi Sign Language.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-language"></i>
            Sentence-Level Translation
          </h4>

          <p class="card-text">
            Extend the system from individual static signs to continuous
            gesture sequences and sentence-level translation.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-mobile-alt"></i>
            Mobile Accessibility
          </h4>

          <p class="card-text">
            Develop a mobile-friendly application to make the recognition
            system more accessible for everyday use.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    Project Highlights
  </h2>

  <p>
    This project demonstrates practical experience in
    <strong>deep learning, computer vision, object detection, custom dataset
    development, YOLOv10 model training, and sign language recognition</strong>.
    It combines technical innovation with a socially meaningful objective:
    improving communication accessibility for people who rely on
    Bangladeshi Sign Language.
  </p>

  <h2 class="project-section-title">
    GitHub Repository
  </h2>

  <p>
    The complete source code of the project is available in the GitHub
    repository.
  </p>

  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/SIGN_LANGUAGE_DETECTION"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>