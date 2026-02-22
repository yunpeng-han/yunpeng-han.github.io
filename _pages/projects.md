---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Reinforcement Learning Based Motion Planning: Lane Change
======
*March 2025 – May 2025*

* Developed a reinforcement learning-based motion planning framework for autonomous vehicle lane changes using the CARLA simulator.
* Designed an end-to-end vision-based motion planning system that maps raw RGB camera inputs directly to acceleration and steering commands, enabling real-time navigation in dynamic traffic scenarios.
* Trained collision-avoidance policies across varying speeds with Proximal Policy Optimization (PPO).
* Conducted extensive simulation testing to validate the safety and reliability of lane-change maneuvers.

Optimal Trajectory Planning for Autonomous Parking
======
*2024*

* Proposed a coupled bi-stage trajectory planner in cluttered, unstructured environments, combining RRT\* with Reeds–Shepp curves and cubic-spline smoothing to generate feasible initial paths for optimal control.
* Formulated exact-geometry collision-avoidance constraints via dual convex reformulation and obstacle reduction, and implemented the resulting nonlinear program in CasADi/IPOPT for real-time–feasible optimization.
* Validated the method in 100 tight-space parking/exit scenarios, achieving smooth, comfort-aware trajectories and reducing computation time by up to ~90% compared with single-stage optimal-control baselines.
