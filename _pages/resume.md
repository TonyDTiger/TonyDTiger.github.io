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

Verification & Validation Testing: 
* Unit testing
* SIL/HIL integration testing
* Monte Carlo analysis

Flight Operations: 
* On-orbit commissioning and anomaly resolution
* Telmetry trending
* Procedure development

Fault Management:
* Fault Tree Analysis (FTA)
* Autonomous fault detection/response
* Test case development

---

Work experience
======
GN&C Engineer | Boeing, Everett, WA | September 2023 - Present 
* Perform safety and fault tolerance analyses for flight control algorithms on the 777X fixed wing aircraft, ensuring certification compliance and flight controls robustness.
* Improved the fault tree failure database by integrating electrical wiring zone failure rates derived from wiring diagrams and component-level reliability data. 
* Define new system-level safety requirements following decomposition and traceability processes.
* Led fault tree and branch termination analyses for a spacecraft’s GN&C subsystem to identify autonomous fault detection and response logic.
* Defined and documented autonomy software interface commands and telemetry.
* Improved MATLAB tools for pointing jitter frequency domain analysis.
  
GN&C Engineer | Ball Aerospace, Boulder, CO | July 2019 – August 2023
* Investigated and resolved GPS and star tracker anomalies on-orbit by trending telemetry and coordinating with operations team, supplier, and customer.
* Developed tools to process ground test and on-orbit telemetry data, reducing turnaround time for anomaly investigations and calibrations.
* Validated GN&C hardware and subsystem functionality through hardware-in-loop and software-in-loop tests in a cleanroom environment, resolving anomalies in real time and leading to mission readiness.
* Conducted Monte Carlo analyses in a 6-DOF nonlinear simulation environment to verify pointing control and safing requirements for two spacecraft.
* Led cross-functional meetings to analyze and validate IXPE’s boom deployment sequence and contingency plans, contributing to a successful in-space deployment.
* Established a product baseline of GN&C algorithm unit tests with the flight software team.
* Developed and verified PID-based thermal control algorithms with MATLAB nonlinear simulations, ensuring spacecraft components remained within strict operational temperature limits.
* Developed and validated a 2-axis gimbal multi-body model in MATLAB/Simulink to ensure accurate antenna pointing performance within a 6-DOF nonlinear simulation environment.
* Tuned coarse sun sensor and gimbal motor simulation models using vendor and in-house test data for improved simulation fidelity.

Technical Aide | Ball Aerospace, Boulder, CO | August 2018 – July 2019
* Developed MATLAB/STK scripts to generate de-orbit burn sequences and scenario generation.
* Executed high-fidelity ADCS simulations for spacecraft attitude control performance evaluation.

Systems Integration & Test Intern | Ball Aerospace, Boulder, CO | June 2018 – August 2018
* Analyzed the relationship between the observatory's orientation and thermal heater power loads to explore the possibility of reducing heater power loads and radiator size by adjusting the mission design.
* Automated telemetry-to-Systems Tool Kit animation generation, enabling visual flight data review.

Course Assistant | Applied Mathematics & Ann and H.J. Smead Aerospace Engineering Departments, Boulder, CO | July 2017 – May 2019
* Held office hours to assist students, compile homework/project solutions, grade course material and help assess grades. Courses: Orbital Mechanics/Attitude Dynamics and Control, Statistical Methods.

---

Projects
======
Personal GN&C Projects | August 2024 - Present
* [Check out my Porfolio page!](https://tonydtiger.github.io//portfolio/)

CubeSat Design (SolarCube) | January 2018– May 2018
University of Colorado Boulder, Boulder, CO 
* Created a closed-loop 6-DOF simulator from scratch to evaluate actuator sizing, PD control response, momentum management, and available time to transit for a rigid body satellite under atmospheric, graviational, and solar radiation disturbance torques.
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
