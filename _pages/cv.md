---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Aerospace Engineering, University of Colorado Boulder, 2019
* B.S. in Aerospace Engineering, University of Colorado Boulder, 2019

Skills
======
* Flight Controls & GN&C: 
  * 6-DOF simulations, linear Kalman filters, linear control theory, PID controllers, attitude dynamics
* Testing & Validation: 
  * SIL/HIL integration testing, unit testing, Monte Carlo performance analysis, requirements verification & validation
* Modeling & Simulation: 
  * MATLAB/Simulink, rigid body and multi-body dynamics, actuator modeling
* Mission Operations: 
  * Anomaly resolution, telemetry analysis, autonomous fault detection/response
* Software & Tools: 
  * Python, C++, STK, ODTK, Git, Apache Subversion

Work experience
======
* GN&C Engineer | September 2023 - Present
* Boeing, Everett, WA
  * Perform safety and fault tolerance analyses for flight control algorithms on the 777X fixed wing aircraft
  * Developed MATLAB tools for pointing jitter frequency domain analysis
  * Defined and documented software interface commands and telemetry for autonomy software and satellite subsystems
  * Led fault tree and branch termination analyses for a satellite’s GN&C subsystem and identified the autonomous fault detection and response measures needed to achieve mission objectives
  * Supported internal and customer design reviews for

* GN&C Engineer | July 2019 – August 2023
* Ball Aerospace, Boulder, CO
  * Designed and unit tested PID-based heater control laws in MATLAB to meet tight thermal performance requirements
  * Developed and validated a 2-axis gimbal multi-body model using Newton-Euler equations to verify antenna pointing performance in MATLAB/Simulink
  * Conducted Monte Carlo analyses of 6-DOF spacecraft simulations to verify pointing performance and safing requirements
  * Supported software-in-loop (SIL)/hardware-in-loop (HIL) tests, executing functional and open-loop control law testing on hardware in a cleanroom environment
  * Tuned coarse sun sensor and gimbal motor simulation models using vendor and in-house test data for improved simulation fidelity
  * Established a product baseline of GN&C algorithm unit tests for the embedded flight software team

* Technical Aide | August 2018 – July 2019
* Ball Aerospace, Boulder, CO
  * Developed MATLAB/STK scripts to generate de-orbit burn sequences and scenario generation
  * Executed high-fidelity ADCS simulations for spacecraft attitude control performance evaluation

Projects
======
* Personal GN&C Projects | August 2024 - Present
  * Check out the Porfolio page!
* CubeSat Design (SolarCube) | January 2018– May 2018
* University of Colorado Boulder, Boulder, CO 
  * Created a closed-loop 6-DOF simulator from scratch to evaluate actuator sizing, PD control response, and momentum management.
* Autonomous Capture of a 2-DOF CubeSat | August 2016 – May 2017
* University of Colorado Boulder, Boulder, CO
  * Designed and tested MATLAB algori

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
