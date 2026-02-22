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
* Ph.D. Candidate in Electrical Engineering, Louisiana State University, Baton Rouge, LA (Expected 2027)
  * GPA: 3.87 | Research Area: Motion Planning & Control, Reinforcement Learning
* M.S. in Mechanical Engineering, Florida Institute of Technology, Melbourne, FL, May 2019
  * GPA: 3.83
* M.E. in Mechanical Engineering, Shijiazhuang Tiedao University, Hebei, China, Jun 2020
* B.E. in Mechanical Design, Manufacturing & Automation, Shijiazhuang Tiedao University, Hebei, China, Jun 2016

Work Experience
======
* Feb 2022 – Aug 2023: ADAS Planning & Control Engineer (Full time)
  * DESAY SV Automotive, Huizhou, China
  * Key Expertise: Motion Planning Algorithms, Motion Control (LQR/PID/MPC), Hybrid A\*, Gauss Pseudo-spectral Optimization, Bézier/Quintic Polynomial Interpolation, MIL/HIL Validation, MATLAB/Simulink, C++
  * Developed Automatic Parking Assist (APA): utilized Gauss Pseudo-Spectral method to generate optimal collision-free paths; achieved 90%+ success rate across 300+ test cases.
  * Developed "Back to Origin" path planning for driving academy: implemented Hybrid A\* + Reeds-Shepp and Arc-Quintic + Polynomial Planning, reducing planning time by 85%.
  * Implemented LQR, PID, and MPC for lateral/longitudinal vehicle control under AUTOSAR architecture.

* Aug 2020 – Jul 2021: Embedded Software Engineer (Full time)
  * DALI Technology Robot R&D, Hangzhou, China
  * Developed forward and inverse kinematic models for an all-terrain wheeled mobile robot.
  * Designed and tuned PID controllers for each wheel for smooth, stable tracking performance.
  * Programming for mobile robots using STM32 microcontroller (C, FreeRTOS).

Academic Projects
======
* **Reinforcement Learning Based Motion Planning: Lane Change** (March 2025 – May 2025)
  * Developed a RL-based motion planning framework for autonomous vehicle lane changes using CARLA simulator.
  * Designed an end-to-end vision-based system mapping raw RGB camera inputs to acceleration and steering commands.
  * Trained collision-avoidance policies using Proximal Policy Optimization (PPO).

* **Optimal Trajectory Planning for Autonomous Parking** (2024)
  * Proposed a coupled bi-stage trajectory planner combining RRT\* with Reeds-Shepp curves and cubic-spline smoothing.
  * Formulated collision-avoidance constraints via dual convex reformulation; implemented in CasADi/IPOPT.
  * Validated in 100 tight-space parking/exit scenarios; reduced computation time by ~90% vs. single-stage baselines.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Automotive Engineering**
  * Trajectory Planning: Interpolation, Hybrid A\*, Optimization-based
  * Motion Control: MPC, LQR, PID, Admittance/Impedance Control
  * Dynamics & Kinematics Modeling: Vehicle Dynamics, 6-DOF Manipulators
  * Simulations: MIL (Prescan / MATLAB / Simulink / CarSim), ROS 2
* **Programming**: C/C++, Python, MATLAB/Simulink, C#
* **Languages**: Chinese (Native), English (Fluent)
