---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

---

Education
======
M.S. in Aerospace Engineering, University of Colorado Boulder, 2019

B.S. in Aerospace Engineering, University of Colorado Boulder, 2019

---

Skills
======
Flight Controls: 
* Linear controllers and control theory
* Linear Kalman filters
* Aircraft dynamics

Testing & Validation: 
* SIL/HIL integration testing, unit testing
* Monte Carlo performance analysis
* Requirements verification & validation

Modeling & Simulation: 
* 6-DOF simulator development 
* Rigid body and multi-body dynamics
* Orbit Mechanics

Fault Management:
* Fault tree analysis
* Autonomous fault detection/response
* Telemetry trending, anomaly resolution

Software & Tools: 
* MATLAB/Simulink, Python, C++, 
* Systems Tool Kit, Orbit Determination Tool Kit
* Git, Apache Subversion

---

Work experience
======
GN&C Engineer | Boeing, Everett, WA | September 2023 - Present 
* Perform safety and fault tolerance analyses for flight control algorithms on the 777X fixed wing aircraft
* Developed MATLAB tools for pointing jitter frequency domain analysis
* Defined and documented software interface commands and telemetry for autonomy software and satellite subsystems
* Led fault tree and branch termination analyses for a satellite’s GN&C subsystem and identified the autonomous fault detection and response measures needed to achieve mission objectives
* Supported internal and customer design reviews for

GN&C Engineer | Ball Aerospace, Boulder, CO | July 2019 – August 2023
* Designed and unit tested PID-based heater control laws in MATLAB to meet tight thermal performance requirements
* Developed and validated a 2-axis gimbal multi-body model using Newton-Euler equations to verify antenna pointing performance in MATLAB/Simulink
* Conducted Monte Carlo analyses of 6-DOF spacecraft simulations to verify pointing performance and safing requirements
* Supported software-in-loop (SIL)/hardware-in-loop (HIL) tests, executing functional and open-loop control law testing on hardware in a cleanroom environment
* Tuned coarse sun sensor and gimbal motor simulation models using vendor and in-house test data for improved simulation fidelity
* Established a product baseline of GN&C algorithm unit tests for the embedded flight software team

Technical Aide | Ball Aerospace, Boulder, CO | August 2018 – July 2019
* Developed MATLAB/STK scripts to generate de-orbit burn sequences and scenario generation
* Executed high-fidelity ADCS simulations for spacecraft attitude control performance evaluation

Systems Integration & Test Intern | Ball Aerospace, Boulder, CO | June 2018 – August 2018
* Analyzed the relationship between the observatory's orientation and thermal heater power loads to explore the possibility of reducing heater power loads and radiator size by adjusting the mission design
* Developed a MATLAB script to autonomously create STK simulations from telemetry flight data

Course Assistant | Applied Mathematics & Ann and H.J. Smead Aerospace Engineering Departments, Boulder, CO | July 2017 – May 2019
* Held office hours to assist students, compile homework/project solutions, grade course material and help assess grades. Courses: Orbital Mechanics/Attitude Dynamics and Control, Statistical Methods

---

Projects
======
Personal GN&C Projects | August 2024 - Present
* [Check out my Porfolio page!](https://tonydtiger.github.io//portfolio/)

CubeSat Design (SolarCube) | January 2018– May 2018
University of Colorado Boulder, Boulder, CO 
* Created a closed-loop 6-DOF simulator from scratch to evaluate actuator sizing, PD control response, and momentum management.
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
