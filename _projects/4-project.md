---
layout: page
title: Learning Management System
description: A full-stack Learning Management System with React, Node.js, Express, MongoDB, and Docker.
img: assets/img/12.jpg
importance: 1
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
      <i class="fas fa-graduation-cap"></i>
    </div>

    <div>
      <h1 class="project-title">
        Learning Management System
      </h1>

      <p class="project-subtitle">
        A full-stack Learning Management System for B-JET.
      </p>
    </div>

  </div>


  <div class="project-description">

    Developed a full-stack <strong>Learning Management System (LMS)</strong>
    consisting of separate frontend and backend services. The backend is
    built using <strong>Node.js, Express, and MongoDB</strong>, while the
    frontend is developed using <strong>React</strong>.

    The project is containerized using <strong>Docker</strong> and
    <strong>Docker Compose</strong>, allowing the frontend and backend
    services to be built and launched together in a local development
    environment.

  </div>

Technology:,, Toolkit,Material ,,,.
  <div class="project-tags">

    <span class="project-tag">React</span>
    <span class="project-tag">React</span>
    <span class="project-tag">NRedux</span>
    <span class="project-tag">UI</span>
    <span class="project-tag">TypeScript</span>
    <span class="project-tag">Express.js</span>
    <span class="project-tag">Node.js</span>
    <span class="project-tag">Mongoose</span>

  </div>


  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Learning-Management-System"
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
    The Learning Management System (LMS) is a full-stack web application
    developed for B-JET. The system consists of both frontend and backend
    services, providing a structured architecture for developing and
    running the application.
  </p>


  <h2 class="project-section-title">
    System Architecture
  </h2>

  <div class="row justify-content-sm-center">

    <div class="col-sm-6 mt-3 mt-md-0">

      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Frontend
          </h4>

          <p class="card-text">
            The frontend of the LMS is developed using
            <strong>React</strong>.
          </p>

        </div>
      </div>

    </div>


    <div class="col-sm-6 mt-3 mt-md-0">

      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Backend
          </h4>

          <p class="card-text">
            The backend is developed using
            <strong>Node.js, Express, and MongoDB</strong>.
          </p>

        </div>
      </div>

    </div>

  </div>


  <h2 class="project-section-title">
    Key Features
  </h2>

  <ul>

    <li>
      Full-stack Learning Management System architecture.
    </li>

    <li>
      React-based frontend application.
    </li>

    <li>
      Node.js and Express-based backend.
    </li>

    <li>
      MongoDB database integration.
    </li>

    <li>
      Separate frontend and backend services.
    </li>

    <li>
      Docker-based application environment.
    </li>

    <li>
      Docker Compose configuration for running the services together.
    </li>

  </ul>


  <h2 class="project-section-title">
    Technology Stack
  </h2>

  <p>
    <strong>Frontend:</strong> React
  </p>

  <p>
    <strong>Backend:</strong> Node.js, Express
  </p>

  <p>
    <strong>Database:</strong> MongoDB
  </p>

  <p>
    <strong>Deployment & Containerization:</strong> Docker, Docker Compose
  </p>


  <h2 class="project-section-title">
    Running the Project
  </h2>

  <p>
    The project can be run locally using Docker Compose. After configuring
    the required environment variables in the backend directory, the
    frontend and backend services can be built and started together using
    Docker Compose.
  </p>


  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Learning-Management-System"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>