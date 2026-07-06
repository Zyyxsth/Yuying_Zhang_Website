---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
lang: en
alternate_url: /zh/cv/
redirect_from:
  - /resume
---

Education
======

- **M.S. in Control Science and Engineering**, Sun Yat-sen University, Sep. 2024–Jun. 2027 (expected)<br>
  GPA: 3.84/4.00 · Rank: 2/30 · First-Class Outstanding Student Scholarship (2025) · Second-Class Outstanding Student Scholarship (2024)
- **B.Eng. in Intelligent Science and Technology**, Sun Yat-sen University, Sep. 2020–Jun. 2024<br>
  GPA: 3.90/4.00 · Rank: 15/225 · Second-Class Outstanding Student Scholarship (2021, 2023)

Research and industry experience
======

### EngineAI — Motion Control Algorithm Intern

**May 2026–Present**

- Developed high-dynamic humanoid motion policies based on BeyondMimic, including sweeping kicks and aerial spinning kicks, with successful deployment in MuJoCo and on the T800 humanoid robot.
- Trained AMP-based omnidirectional boxing-style locomotion for T800 and addressed weak posture support, reward collapse, style ambiguity, and directional performance imbalance.

### Benmo Technology — Reinforcement Learning Motion Control Algorithm Intern

**Oct. 2025–Dec. 2025**

- Developed autonomous stair-climbing control for the D1 wheeled-legged robot using constrained reinforcement learning.
- Built a joint-level hard-constrained policy optimization method based on NP3O and a privileged learning framework with Barlow Twins self-supervision.
- Completed the full Sim-to-Real pipeline and validated the method through ablation and comparative experiments.

Selected projects
======

### Threat-Aware UAV Dodging with an Onboard RGB-D Camera

**First author · Dec. 2024–Sep. 2025**

- Led the complete perception-to-control system, including 3D human keypoint recovery, projectile trajectory prediction, uncertainty-aware threat modeling, and evasive trajectory optimization.
- Achieved a 6 m detection range, 26.4 ms perception latency on CPU-only hardware, and a 96.67% dodging success rate in real-world experiments.
- Published as first author in *IEEE Robotics and Automation Letters*.

### CGN–Hong Kong–SYSU Inspection Project

**Planning and Control Lead · Apr. 2025–Aug. 2025**

- Developed mapping, planning, control, and state-machine modules for autonomous wheeled-legged robot inspection in nuclear power plant environments.
- Implemented local grid mapping, dynamically feasible trajectory optimization, online replanning, and MPC trajectory tracking.

Technical skills
======

- **Robotics:** reinforcement learning, wheeled-legged robot control, humanoid locomotion, MPC, path planning, trajectory optimization
- **Simulation:** Isaac Lab, MuJoCo
- **Middleware and tools:** ROS 1, ROS 2, RViz, Linux, Git, Docker
- **Engineering:** Sim-to-Real, real-world deployment, multi-scenario experimental validation

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
