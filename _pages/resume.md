---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

---

Education
======
B.S./M.S. in Aerospace Engineering, University of Colorado Boulder, 2019

---

Skills
======
Fault Management:
* Fault Tree Analysis (FTA)
* Autonomous fault detection/response
* Test case development

Verification & Validation Testing: 
* SIL/HIL integration testing
* Unit testing
* Monte Carlo analysis

Flight Operations: 
* On-orbit commissioning and anomaly resolution
* Telmetry trending
* Procedure development

State Estimation and Controls: 
* Linear controllers and control theory
* Linear Kalman filters

Modeling & Simulation: 
* 6-DOF simulator development 
* Rigid body and multi-body dynamics
* Flight dynamics, orbital mechanics

Software & Tools: 
* MATLAB/Simulink, Python, C++, 
* Systems Tool Kit, Orbit Determination Tool Kit
* Git, Apache Subversion
* Microsoft Office

---

Work experience
======
GN&C Engineer | Boeing, Everett, WA | September 2023 - Present 
* Perform FTA to verify probabilistic safety requirements for flight control algorithms on the Boeing 
777X, contributing numerical evidence toward system safety certification.
* Improved the fault tree failure database by integrating electrical wiring zone failure rates derived from 
wiring diagrams and component-level reliability data. 
* Define safety requirements following decomposition and traceability processes.
* Led fault tree and branch termination analyses for a satellite’s GN&C subsystem and identified the autonomous fault detection and response measures needed to achieve mission objectives.
* Defined and documented autonomy software interface commands and telemetry.
* Improved MATLAB tools for pointing jitter frequency domain analysis.
  
GN&C Engineer | Ball Aerospace, Boulder, CO | July 2019 – August 2023
* Investigated and resolved GPS receiver and star tracker anomalies on-orbit, coordinating with operations team, supplier, and customer and tracking root cause analysis with Jira Service Management.
* Developed tools to process test and on-orbit telemetry data, reducing turnaround time for anomaly investigations and calibrations.
* Supported GN&C subsystem SIL and HIL tests to validate GN&C hardware and subsystem functionality and resolved anomalies real-time in a cleanroom environment to maintain schedule.
* Conducted Monte Carlo analyses of 6-DOF spacecraft simulations with fault injection to quantify the probabilistic reliability of GN&C performance and verify pointing performance and safing requirements.
* Led cross-functional meetings to refine and verify IXPE’s boom deployment sequence and its contingency responses.
* Established a product baseline of GN&C algorithm unit tests for the flight software team.
* Designed and tuned control algorithms for spacecraft bus thermal control systems to meet tight temperature range requirements.
* Developed and validated a 2-axis gimbal multi-body model using Newton-Euler equations to verify antenna pointing performance in MATLAB/Simulink.
* Tuned coarse sun sensor and gimbal motor simulation models using vendor and in-house test data for improved simulation fidelity.

Technical Aide | Ball Aerospace, Boulder, CO | August 2018 – July 2019
* Developed MATLAB/STK scripts to generate de-orbit burn sequences and scenario generation.
* Executed high-fidelity ADCS simulations for spacecraft attitude control performance evaluation.

Systems Integration & Test Intern | Ball Aerospace, Boulder, CO | June 2018 – August 2018
* Analyzed thermal and orientation dependencies to optimize mission design.
* Automated STK simulations from flight telemetry.

Course Assistant | Applied Mathematics & Ann and H.J. Smead Aerospace Engineering Departments, Boulder, CO | July 2017 – May 2019
* Held office hours to assist students, compile homework/project solutions, grade course material and help assess grades. Courses: Orbital Mechanics/Attitude Dynamics and Control, Statistical Methods.

---

Projects
======
Personal GN&C Projects | August 2024 - Present
* [Check out my Porfolio page!](https://tonydtiger.github.io//portfolio/)

CubeSat Design (SolarCube) | January 2018– May 2018
University of Colorado Boulder, Boulder, CO 
* Created a closed-loop 6-DOF simulator from scratch to evaluate actuator sizing, PD control response, momentum management, and available time to transit.
* [Cool satellite ground tracking simulation that I put together!](https://drive.google.com/file/d/1UGWogkpv6JH0efh2DyCAycW9bmp2JZB5/view)

Autonomous Capture of a 2-DOF CubeSat | August 2016 – May 2017
University of Colorado Boulder, Boulder, CO
* Designed and tested MATLAB algorithms for autonomous target capture; presented work in PDR/CDR reviews and published in AIAA.
* [My team's final presentation](https://www.colorado.edu/aerospace/sites/default/files/attached-files/cascade_sfr.pdf)

---

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
