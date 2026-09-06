---
layout: page
title: University Cafeteria Management System
description: A full-stack University Cafeteria Management System with role-based features for customers, administrators, managers, cashiers, and delivery personnel.
img: assets/img/University_Cafe.png
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
      <i class="fas fa-utensils"></i>
    </div>

    <div>
      <h1 class="project-title">
        University Cafeteria Management System
      </h1>

      <p class="project-subtitle">
        A full-stack web-based cafeteria management and food ordering system.
      </p>
    </div>

  </div>


  <div class="project-description">

    Developed a full-stack <strong>University Cafeteria Management System</strong>
    designed to simplify food ordering, cafeteria operations, inventory
    management, payment processing, delivery, and administrative activities.
    The system provides separate role-based functionalities for
    <strong>Customers, Admins, Managers, Cashiers, and Delivery Personnel</strong>.
    
    Customers can browse the menu, place and customize orders, view order
    history, save favorite orders, and provide feedback. Administrators and
    managers can manage food items, users, orders, inventory, staff schedules,
    sales, and customer feedback, while cashiers handle payments and delivery
    personnel manage food delivery and order status.

  </div>


  <div class="project-tags">

    <span class="project-tag">React</span>
    <span class="project-tag">Redux</span>
    <span class="project-tag">JavaScript</span>
    <span class="project-tag">Node.js</span>
    <span class="project-tag">Express.js</span>
    <span class="project-tag">MongoDB</span>
    <span class="project-tag">Mongoose</span>
    <span class="project-tag">REST API</span>
    <span class="project-tag">Role-Based Access</span>

  </div>


  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Ecommerce-Website"
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
    The <strong>University Cafeteria Management System</strong> is a
    full-stack web application developed to provide an efficient and
    centralized platform for managing university cafeteria operations.
    The system integrates food ordering, payment processing, inventory,
    delivery management, customer feedback, and administrative activities
    into a single platform.
  </p>

  <p>
    The application follows a <strong>role-based architecture</strong>,
    allowing each type of user to access the features relevant to their
    responsibilities. This improves operational efficiency while providing
    customers with a convenient way to order food and track their orders.
  </p>


  <h2 class="project-section-title">
    User Roles & Features
  </h2>


  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 role-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user"></i>
            Customer
          </h4>

          <ul>
            <li>Browse and order food items from the menu.</li>
            <li>View previous orders and order history.</li>
            <li>Customize food orders and specify dietary requirements.</li>
            <li>Save favorite orders for future use.</li>
            <li>Provide feedback and ratings for food items.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 role-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user-shield"></i>
            Admin
          </h4>

          <ul>
            <li>Add, edit, and delete food items and menus.</li>
            <li>Manage user accounts and user roles.</li>
            <li>View and manage orders and order history.</li>
            <li>Generate sales, revenue, and feedback reports.</li>
            <li>Monitor inventory and stock availability.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 role-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user-tie"></i>
            Manager
          </h4>

          <ul>
            <li>Manage staff schedules and shifts.</li>
            <li>Monitor sales and revenue trends.</li>
            <li>Analyze customer feedback and ratings.</li>
            <li>Manage menu items, promotions, and pricing decisions.</li>
            <li>Monitor food quality and cafeteria hygiene standards.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 role-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-cash-register"></i>
            Cashier
          </h4>

          <ul>
            <li>Process customer orders and payments.</li>
            <li>Manage cash registers and POS operations.</li>
            <li>Handle refunds and returns.</li>
            <li>Maintain cleanliness and orderliness of the cafeteria.</li>
            <li>Assist customers with questions and order-related issues.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 role-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-motorcycle"></i>
            Delivery Personnel
          </h4>

          <ul>
            <li>Receive and fulfill delivery orders.</li>
            <li>Track order progress and update delivery status.</li>
            <li>Maintain accurate delivery records and receipts.</li>
            <li>Ensure timely delivery of food orders.</li>
          </ul>

        </div>
      </div>
    </div>

  </div>


  <h2 class="project-section-title">
    Key Features
  </h2>

  <ul>

    <li>
      Role-based cafeteria management system.
    </li>

    <li>
      Online food browsing and ordering.
    </li>

    <li>
      Food order customization and dietary preference support.
    </li>

    <li>
      Customer order history and favorite orders.
    </li>

    <li>
      Customer feedback and food rating system.
    </li>

    <li>
      Food menu and inventory management.
    </li>

    <li>
      User account and role management.
    </li>

    <li>
      Order and payment management.
    </li>

    <li>
      Sales, revenue, and customer feedback monitoring.
    </li>

    <li>
      Staff scheduling and shift management.
    </li>

    <li>
      Delivery order tracking and status updates.
    </li>

    <li>
      Refund and return management.
    </li>

  </ul>


  <h2 class="project-section-title">
    Technology Stack
  </h2>

  <p>
    <strong>Frontend:</strong> React, Redux, JavaScript
  </p>

  <p>
    <strong>Backend:</strong> Node.js, Express.js
  </p>

  <p>
    <strong>Database:</strong> MongoDB, Mongoose
  </p>

  <p>
    <strong>Architecture:</strong> Full-stack REST-based web application
  </p>

  <p>
    <strong>Access Control:</strong> Role-based user management
  </p>


  <h2 class="project-section-title">
    System Modules
  </h2>

  <div class="row justify-content-sm-center">

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Food & Menu
          </h4>

          <p class="card-text">
            Manage food items, categories, prices, availability, and menus.
          </p>

        </div>
      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Order Management
          </h4>

          <p class="card-text">
            Manage customer orders, order history, customization, and
            delivery status.
          </p>

        </div>
      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Inventory
          </h4>

          <p class="card-text">
            Monitor stock levels and food availability to support cafeteria
            operations.
          </p>

        </div>
      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Payment
          </h4>

          <p class="card-text">
            Support order payment processing, POS operations, refunds, and
            transaction management.
          </p>

        </div>
      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Delivery
          </h4>

          <p class="card-text">
            Manage delivery orders, progress tracking, status updates, and
            delivery records.
          </p>

        </div>
      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Reports & Feedback
          </h4>

          <p class="card-text">
            Monitor sales, revenue, customer ratings, and feedback to support
            operational decisions.
          </p>

        </div>
      </div>
    </div>

  </div>


  <h2 class="project-section-title">
    GitHub Repository
  </h2>

  <p>
    The complete source code of the University Cafeteria Management System
    is available in the GitHub repository.
  </p>


  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Ecommerce-Website"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>