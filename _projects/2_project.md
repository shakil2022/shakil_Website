---
layout: page
title: Training Program Management System
description: A web-based Training Program Management System for managing courses, trainees, enrollment, payments, communication, and training activities.
img: assets/img/training-management.jpg
importance: 4
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
      <i class="fas fa-chalkboard-teacher"></i>
    </div>

    <div>
      <h1 class="project-title">
        Training Program Management System
      </h1>

      <p class="project-subtitle">
        A web-based platform for managing training programs, courses,
        trainees, enrollment, payments, and communication.
      </p>
    </div>

  </div>

  <div class="project-description">

    Developed a <strong>Training Program Management System (TPMS)</strong>
    designed to streamline the administration, organization, and delivery
    of training programs. The system provides a centralized platform for
    managing courses, trainees, enrollment, payments, communication, and
    training-related activities.

    The application was developed using <strong>PHP</strong> with
    <strong>MySQL</strong> for database management. The user interface
    incorporates <strong>HTML, CSS, JavaScript, and Bootstrap</strong>,
    while GitHub was used for source-code management and collaboration.

  </div>

  <div class="project-tags">
    <span class="project-tag">PHP</span>
    <span class="project-tag">MySQL</span>
    <span class="project-tag">HTML</span>
    <span class="project-tag">CSS</span>
    <span class="project-tag">JavaScript</span>
    <span class="project-tag">Bootstrap</span>
    <span class="project-tag">Web Application</span>
    <span class="project-tag">Training Management</span>
    <span class="project-tag">Live Chat</span>
    <span class="project-tag">Online Payment</span>
  </div>

  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Training-Program-Management-System"
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
    The <strong>Training Program Management System (TPMS)</strong> is a
    web-based platform developed to support the administration,
    documentation, tracking, and management of training programs.
    The system provides a centralized environment where administrators,
    instructors, and trainees can perform their respective activities.
  </p>

  <p>
    The system allows administrators or instructors to create and maintain
    course categories, add and manage courses, monitor trainee enrollment,
    communicate with trainees, and configure payment and language settings.
    Trainees can create accounts, manage their profiles, search for courses,
    add courses to a cart, purchase courses, review courses, view enrolled
    courses, and communicate through the live chat facility.
  </p>

  <div class="row justify-content-sm-center">

    <div class="col-sm-8 mt-3 mt-md-0">
      {% include figure.liquid
        loading="eager"
        path="assets/img/training-management-1.jpg"
        title="Training Program Management System Dashboard"
        class="img-fluid rounded z-depth-1"
      %}
    </div>

    <div class="col-sm-4 mt-3 mt-md-0">
      {% include figure.liquid
        loading="eager"
        path="assets/img/training-management-2.jpg"
        title="Training Program Management System Course Management"
        class="img-fluid rounded z-depth-1"
      %}
    </div>

  </div>

  <div class="caption">
    The Training Program Management System provides centralized management
    of training programs, courses, trainees, enrollment, and related
    activities.
  </div>

  <h2 class="project-section-title">
    System Features
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user-shield"></i>
            Admin &amp; Instructor Management
          </h4>

          <ul>
            <li>Provides a dedicated admin/instructor dashboard.</li>
            <li>Creates and manages course categories.</li>
            <li>Adds, updates, and deletes courses.</li>
            <li>Manages trainee enrollment.</li>
            <li>Controls payment and language settings.</li>
          </ul>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user-graduate"></i>
            Trainee Management
          </h4>

          <ul>
            <li>Provides trainee registration and login.</li>
            <li>Allows users to view and update their profiles.</li>
            <li>Allows trainees to search for courses.</li>
            <li>Supports course enrollment and purchasing.</li>
            <li>Displays enrolled courses.</li>
          </ul>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-comments"></i>
            Live Chat
          </h4>

          <ul>
            <li>Provides direct communication between trainees and instructors.</li>
            <li>Helps trainees ask questions about courses.</li>
            <li>Supports communication about enrollment and payment.</li>
            <li>Improves interaction between trainees and instructors.</li>
          </ul>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-credit-card"></i>
            Online Payment
          </h4>

          <ul>
            <li>Supports online course purchasing.</li>
            <li>Provides payment configuration for administrators.</li>
            <li>Supports different currency options.</li>
            <li>Allows trainees to confirm course payments.</li>
          </ul>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    System Components
  </h2>

  <div class="row">

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Admin Dashboard</h4>

          <p class="card-text">
            Provides administrative control over courses, categories,
            trainees, enrollment, payments, and language settings.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Course Management</h4>

          <p class="card-text">
            Allows administrators or instructors to add, update, delete,
            categorize, and maintain training courses.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Trainee Management</h4>

          <p class="card-text">
            Maintains registered trainees and provides access to their
            enrollment and course-related information.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Enrollment Management</h4>

          <p class="card-text">
            Tracks course enrollment history and provides information
            about overall and pending enrollment.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Payment Management</h4>

          <p class="card-text">
            Provides payment-related configuration and supports course
            purchasing by trainees.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">User Profile</h4>

          <p class="card-text">
            Provides trainees with a profile containing their account
            information and allows profile information to be updated.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    User Workflow
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user-plus"></i>
            1. Registration
          </h4>

          <p class="card-text">
            New instructors and trainees first create an account by
            providing the required information.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-sign-in-alt"></i>
            2. Login
          </h4>

          <p class="card-text">
            Users log into the system using their registered username
            and password. The system provides separate administrative
            and user-oriented functionality.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-search"></i>
            3. Course Search
          </h4>

          <p class="card-text">
            Trainees can browse and search available courses using
            course categories to find their desired training program.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-shopping-cart"></i>
            4. Course Purchase
          </h4>

          <p class="card-text">
            Trainees can add courses to their cart, purchase their
            selected courses, and access the courses after enrollment.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-comments"></i>
            5. Communication
          </h4>

          <p class="card-text">
            Trainees can communicate directly with instructors through
            the live chat facility when they need assistance.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-book-open"></i>
            6. Course Access
          </h4>

          <p class="card-text">
            After purchasing and enrolling in a course, trainees can
            view their enrolled courses and access the available
            course materials.
          </p>

        </div>
      </div>
    </div>

  </div>

  <div class="row justify-content-sm-center">

    <div class="col-sm-10 mt-3 mt-md-0">
      {% include figure.liquid
        loading="eager"
        path="assets/img/training-management-3.jpg"
        title="Training Program Management System User Interface"
        class="img-fluid rounded z-depth-1"
      %}
    </div>

  </div>

  <div class="caption">
    The system supports course discovery, enrollment, purchasing,
    course access, profile management, and communication between
    trainees and instructors.
  </div>

  <h2 class="project-section-title">
    Technology Stack
  </h2>

  <div class="table-responsive">

    <table class="table table-bordered">

      <thead>
        <tr>
          <th>Technology / Tool</th>
          <th>Purpose</th>
        </tr>
      </thead>

      <tbody>

        <tr>
          <td>PHP</td>
          <td>Server-side application development</td>
        </tr>

        <tr>
          <td>MySQL</td>
          <td>Database management and data storage</td>
        </tr>

        <tr>
          <td>HTML</td>
          <td>Web page structure and content</td>
        </tr>

        <tr>
          <td>CSS</td>
          <td>User interface styling</td>
        </tr>

        <tr>
          <td>JavaScript</td>
          <td>Client-side web functionality</td>
        </tr>

        <tr>
          <td>Bootstrap</td>
          <td>Responsive user interface development</td>
        </tr>

        <tr>
          <td>MySQL Workbench</td>
          <td>Database design and management</td>
        </tr>

        <tr>
          <td>Visual Studio Code</td>
          <td>Development environment</td>
        </tr>

        <tr>
          <td>GitHub</td>
          <td>Version control and code collaboration</td>
        </tr>

      </tbody>

    </table>

  </div>

  <h2 class="project-section-title">
    Technical Attributes
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
          <td>Web-Based Training Management System</td>
        </tr>

        <tr>
          <td>Backend</td>
          <td>PHP</td>
        </tr>

        <tr>
          <td>Database</td>
          <td>MySQL</td>
        </tr>

        <tr>
          <td>Frontend</td>
          <td>HTML, CSS, JavaScript, Bootstrap</td>
        </tr>

        <tr>
          <td>User Roles</td>
          <td>Administrator / Instructor and Trainee</td>
        </tr>

        <tr>
          <td>Course Management</td>
          <td>Course creation, updating, deletion, and categorization</td>
        </tr>

        <tr>
          <td>Enrollment</td>
          <td>Course enrollment and enrollment history</td>
        </tr>

        <tr>
          <td>Payment</td>
          <td>Online course payment and payment configuration</td>
        </tr>

        <tr>
          <td>Communication</td>
          <td>Live chat between trainees and instructors</td>
        </tr>

        <tr>
          <td>Primary Objective</td>
          <td>Centralized management of training programs</td>
        </tr>

      </tbody>

    </table>

  </div>

  <h2 class="project-section-title">
    Key Contributions
  </h2>

  <ul>

    <li>
      <strong>Centralized Management:</strong>
      Provides a centralized platform for managing training-related
      activities.
    </li>

    <li>
      <strong>Course Management:</strong>
      Supports course categories, course creation, maintenance, and
      course-related information.
    </li>

    <li>
      <strong>Online Enrollment:</strong>
      Allows trainees to search for desired courses and enroll in them.
    </li>

    <li>
      <strong>Online Payment:</strong>
      Provides an online purchasing and payment mechanism for courses.
    </li>

    <li>
      <strong>Live Communication:</strong>
      Includes a live chat facility that allows trainees to communicate
      directly with instructors.
    </li>

    <li>
      <strong>User Management:</strong>
      Provides registration, login, profile management, and
      enrolled-course functionality.
    </li>

  </ul>

  <h2 class="project-section-title">
    Future Improvements
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-clipboard-check"></i>
            Assessment System
          </h4>

          <p class="card-text">
            Introduce an assessment system to evaluate trainee knowledge,
            performance, and progress during training programs.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-mobile-alt"></i>
            Mobile Accessibility
          </h4>

          <p class="card-text">
            Extend the platform with improved mobile accessibility so
            trainees can access training services conveniently from
            mobile devices.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-gamepad"></i>
            Gamification
          </h4>

          <p class="card-text">
            Introduce gamification techniques to make training activities
            more engaging and interactive for trainees.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-tachometer-alt"></i>
            Response Optimization
          </h4>

          <p class="card-text">
            Improve system performance and minimize response time for a
            faster and more efficient user experience.
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
    <strong>full-stack web development, PHP application development,
    MySQL database management, responsive interface design, course
    management, user management, online enrollment, payment management,
    and live communication</strong>.
  </p>

  <p>
    The system provides an integrated platform for managing online
    training programs and course purchases while allowing administrators
    or instructors to maintain course information and trainees to
    search, purchase, and access their enrolled courses.
  </p>

  <h2 class="project-section-title">
    Project Report
  </h2>

  <p>
    The project was developed as a semester project at the
    <strong>Institute of Information Technology, Jahangirnagar University</strong>.
    The project report identifies the development technologies as PHP,
    MySQL, HTML, CSS, JavaScript, and Bootstrap.
  </p>

  <p>
    The project team consisted of
    <strong>Mst. Sumiya Siddika, Md. Shakil Ahmed, Shariful Islam,
    and Amit Azim Amit</strong>, under the supervision of
    <strong>Professor Dr. M. Shamim Kaiser</strong>.
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
      href="https://github.com/shakil2022/Training-Program-Management-System"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>