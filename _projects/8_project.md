---
layout: page
title: Automated Fire Detecting and Extinguishing Car
description: An Arduino-based robotic firefighting car that detects fire, moves toward the affected area, and automatically extinguishes the fire using a water-pumping mechanism.
img: assets/img/fire-car.jpg
importance: 6
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
      <i class="fas fa-fire-extinguisher"></i>
    </div>

    <div>
      <h1 class="project-title">
        Automated Fire Detecting and Extinguishing Car
      </h1>

      <p class="project-subtitle">
        An Arduino-based robotic firefighting system for automatic fire detection and extinguishing.
      </p>
    </div>

  </div>


  <div class="project-description">

    Developed an <strong>Arduino-based automated firefighting car</strong>
    designed to detect fire and automatically move toward the affected
    area before extinguishing it using a water pump and sprinkler mechanism.
    The system is intended to reduce human exposure to dangerous
    firefighting environments by performing fire detection and suppression
    tasks with minimal human intervention.

    The robotic vehicle uses sensors as input, an
    <strong>Arduino UNO</strong> as the main control unit, and a water
    pumping mechanism as the fire suppression output. The project focuses
    on improving safety, rapid response, and automation in small and
    potentially hazardous environments.

  </div>


  <div class="project-tags">

    <span class="project-tag">Arduino UNO</span>
    <span class="project-tag">Embedded System</span>
    <span class="project-tag">Robotics</span>
    <span class="project-tag">Fire Detection</span>
    <span class="project-tag">Flame Sensor</span>
    <span class="project-tag">Water Pump</span>
    <span class="project-tag">Sprinkler</span>
    <span class="project-tag">Relay</span>
    <span class="project-tag">L293</span>
    <span class="project-tag">18650 Battery</span>

  </div>


  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Remote-Control-Fire-Detection-Car"
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
    The <strong>Automated Fire Detecting and Extinguishing Car</strong> is
    a robotic firefighting system developed to detect and extinguish fire
    automatically. The project aims to reduce the need for humans to
    directly enter dangerous environments during fire incidents.
  </p>

  <p>
    The system uses sensors to detect fire and sends the detected information
    to the <strong>Arduino UNO</strong> control unit. Based on the sensor
    input, the vehicle moves toward the fire. Once the fire is detected
    within the operating range, the system activates a water pump and
    sprinkler mechanism to spray water toward the fire.
  </p>

  <div class="row justify-content-sm-center">

    <div class="col-sm-8 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/fire-car-1.jpg" title="Automated Fire Detecting and Extinguishing Car" class="img-fluid rounded z-depth-1" %}
    </div>

    <div class="col-sm-4 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/fire-car-2.jpg" title="Fire Detection and Water Pumping System" class="img-fluid rounded z-depth-1" %}
    </div>

  </div>

  <div class="caption">
    The robotic vehicle detects fire using sensors, moves toward the affected area, and activates the water-pumping mechanism to extinguish the fire.
  </div>


  <h2 class="project-section-title">
    System Features
  </h2>


  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-fire"></i>
            Fire Detection
          </h4>

          <ul>
            <li>Detects fire using flame sensors.</li>
            <li>Receives fire-related sensor input.</li>
            <li>Processes sensor information through Arduino UNO.</li>
            <li>Identifies fire within the operating range.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-car"></i>
            Automated Movement
          </h4>

          <ul>
            <li>Moves toward the detected fire.</li>
            <li>Uses sensor input to control vehicle movement.</li>
            <li>Provides a mobile platform for firefighting.</li>
            <li>Designed for operation in small spaces.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-tint"></i>
            Automatic Water Pump
          </h4>

          <ul>
            <li>Activates a water pump after fire detection.</li>
            <li>Uses a pumping mechanism for fire suppression.</li>
            <li>Sprays water toward the detected fire.</li>
            <li>Continues the extinguishing process until the fire stops.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-microchip"></i>
            Arduino Control
          </h4>

          <ul>
            <li>Arduino UNO acts as the main control unit.</li>
            <li>Processes sensor input.</li>
            <li>Controls vehicle movement and output mechanisms.</li>
            <li>Coordinates fire detection and suppression.</li>
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

          <h4 class="card-title">
            Arduino UNO
          </h4>

          <p class="card-text">
            Serves as the main control unit that receives sensor input and
            controls the robotic vehicle and firefighting mechanism.
          </p>

        </div>

      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            Flame Sensor
          </h4>

          <p class="card-text">
            Provides the input used by the system to identify the presence
            of fire within its detection range.
          </p>

        </div>

      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            Water Pump
          </h4>

          <p class="card-text">
            Pumps water toward the fire through the sprinkler mechanism
            after fire detection.
          </p>

        </div>

      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            Relay
          </h4>

          <p class="card-text">
            Provides switching control for the system's output components,
            including the water-pumping mechanism.
          </p>

        </div>

      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            L293 Circuit
          </h4>

          <p class="card-text">
            Used as part of the motor and water-pump control circuitry
            described in the project system model.
          </p>

        </div>

      </div>
    </div>


    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            18650 Battery
          </h4>

          <p class="card-text">
            Provides the electrical power required to initialize and operate
            the automated firefighting car.
          </p>

        </div>

      </div>
    </div>

  </div>


  <h2 class="project-section-title">
    Fire Detection & Extinguishing Workflow
  </h2>


  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-battery-full"></i>
            1. System Initialization
          </h4>

          <p class="card-text">
            The 18650 battery is connected to the automated firefighting
            car and the vehicle is placed on level ground.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-search"></i>
            2. Fire Detection
          </h4>

          <p class="card-text">
            Flame sensors receive input when a fire is present within the
            detection range of the vehicle.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-location-arrow"></i>
            3. Movement Toward Fire
          </h4>

          <p class="card-text">
            The Arduino processes the sensor input and the vehicle moves
            toward the detected fire.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-tint"></i>
            4. Fire Extinguishing
          </h4>

          <p class="card-text">
            The water pump is activated and water is sprayed toward the
            fire through the sprinkler mechanism.
          </p>

        </div>

      </div>
    </div>

  </div>


  <div class="row justify-content-sm-center">

    <div class="col-sm-10 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/fire-car-3.jpg" title="Fire Detection and Extinguishing Process" class="img-fluid rounded z-depth-1" %}
    </div>

  </div>

  <div class="caption">
    The system detects the fire through sensors, moves the vehicle toward the affected area, and activates the water pump to extinguish the fire.
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
          <td>Robotic Firefighting System</td>
        </tr>

        <tr>
          <td>Controller</td>
          <td>Arduino UNO</td>
        </tr>

        <tr>
          <td>Detection Method</td>
          <td>Flame Sensor</td>
        </tr>

        <tr>
          <td>Power Source</td>
          <td>18650 Battery</td>
        </tr>

        <tr>
          <td>Fire Suppression</td>
          <td>Water Pump and Sprinkler</td>
        </tr>

        <tr>
          <td>Motor Control</td>
          <td>L293 Circuit</td>
        </tr>

        <tr>
          <td>Switching</td>
          <td>Relay</td>
        </tr>

        <tr>
          <td>Operating Mode</td>
          <td>Automated Fire Detection and Response</td>
        </tr>

        <tr>
          <td>Vehicle Structure</td>
          <td>Compact and Lightweight Robotic Platform</td>
        </tr>

        <tr>
          <td>Primary Objective</td>
          <td>Fire Detection and Extinguishing</td>
        </tr>

      </tbody>

    </table>

  </div>


  <h2 class="project-section-title">
    Safety & Automation Objectives
  </h2>

  <ul>

    <li>
      <strong>Safety:</strong> Reduce human exposure to dangerous
      firefighting environments.
    </li>

    <li>
      <strong>Rapid Response:</strong> Detect and respond to fire quickly
      within the system's operating range.
    </li>

    <li>
      <strong>Minimal Human Intervention:</strong> Automate the fire
      detection and extinguishing process.
    </li>

    <li>
      <strong>Compact Operation:</strong> Provide a robotic platform that
      can operate in small spaces and areas with limited entrances.
    </li>

  </ul>


  <h2 class="project-section-title">
    Limitations
  </h2>

  <ul>

    <li>
      The flame sensor does not perform well under sunlight.
    </li>

    <li>
      The current system operates only within a limited area.
    </li>

  </ul>


  <h2 class="project-section-title">
    Future Improvements
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-sun"></i>
            Improved Flame Detection
          </h4>

          <p class="card-text">
            Use a higher-performance flame sensor capable of providing
            improved performance under sunlight.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-water"></i>
            Automated Sprinkler
          </h4>

          <p class="card-text">
            Integrate improved automated water-sprinkler functionality for
            more effective fire suppression.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-map-marker-alt"></i>
            GPS Integration
          </h4>

          <p class="card-text">
            Future development can incorporate GPS functionality to enable
            control from remote stations.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-microphone"></i>
            Voice Interaction
          </h4>

          <p class="card-text">
            The system can be further extended with voice-interactive
            functionality and other robotic interfaces.
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
    <strong>Arduino-based robotics, embedded systems, sensor-based fire
    detection, automated vehicle movement, water-pump control, and robotic
    fire suppression</strong>. The compact robotic platform is designed to
    detect fire within a certain range, move toward the affected area, and
    extinguish the fire using a pumping mechanism.
  </p>

  <p>
    According to the project report, experimental operation showed that the
    robot could sense fire accurately within a short time. Its compact body
    also makes it potentially suitable for small spaces and locations with
    limited entrances.
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
      href="https://github.com/shakil2022/Remote-Control-Fire-Detection-Car"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>