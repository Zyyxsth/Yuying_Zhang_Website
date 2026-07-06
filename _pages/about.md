---
permalink: /
title: "About Me"
author_profile: true
lang: en
alternate_url: /zh/
redirect_from:
  - /about/
  - /about.html
  - /cv/
  - /resume
---

I am **Yuying Zhang**, an M.S. student in Control Science and Engineering at [Sun Yat-sen University](https://www.sysu.edu.cn/), expected to graduate in 2027. I received my B.Eng. in Intelligent Science and Technology from Sun Yat-sen University in 2024.

My research focuses on **reinforcement learning, embodied intelligence, and robot planning and control**. I am particularly interested in learning-based locomotion, constrained reinforcement learning, Sim-to-Real transfer, and reliable deployment on humanoid robots, wheeled-legged robots, and UAVs.

Research Interests
======

- Reinforcement learning for robot locomotion and control
- Embodied intelligence and humanoid robotics
- Motion planning, model predictive control, and trajectory optimization
- Sim-to-Real transfer and real-world robot deployment
- Autonomous aerial systems and dynamic obstacle avoidance

Education
======

- **M.S. in Control Science and Engineering**, Sun Yat-sen University, 2024–2027 (expected)
- **B.Eng. in Intelligent Science and Technology**, Sun Yat-sen University, 2020–2024

Publications
======

{% include base_path %}
{% for post in site.publications reversed %}
### [{{ post.title }}]({{ base_path }}{{ post.url }})

{{ post.citation }}

{% if post.paperurl %}[Paper]({{ post.paperurl }}){% endif %}
{% endfor %}

Research & Industry Experience
======

### EngineAI · Motion Control Algorithm Intern

**May 2026–Present**

- Developed high-dynamic humanoid motion policies based on BeyondMimic, including sweeping kicks and aerial spinning kicks, with successful deployment in MuJoCo and on the T800 humanoid robot.
- Trained AMP-based omnidirectional boxing-style locomotion and improved posture support, style clarity, reward stability, and directional consistency.

### DirectDrive Technology · Reinforcement Learning Motion Control Algorithm Intern

**Oct. 2025–Dec. 2025**

- Developed autonomous stair-climbing control for the D1 wheeled-legged robot using constrained reinforcement learning.
- Built a joint-level hard-constrained policy optimization method based on NP3O and a privileged learning framework with Barlow Twins self-supervision.
- Completed the full Sim-to-Real pipeline and validated the method through ablation and comparative experiments.

Selected Projects
======

### [Threat-Aware UAV Dodging with an Onboard RGB-D Camera](https://threat-aware-dodging.github.io/)

**First-listed and co-first author · Dec. 2024–Sep. 2025**

Led the complete perception-to-control system, including 3D human keypoint recovery, projectile trajectory prediction, uncertainty-aware threat modeling, and evasive trajectory optimization. The system achieved a 6 m detection range, 26.4 ms CPU-only perception latency, and a 96.67% dodging success rate in real-world experiments.

### Autonomous Inspection for Nuclear Power Plant Environments

**Planning and Control Lead · Apr. 2025–Aug. 2025**

Developed mapping, planning, control, and task state-machine modules for a wheeled-legged robot inspection system. The system combined LiDAR localization, local grid mapping, dynamically feasible trajectory optimization, online replanning, and MPC trajectory tracking.

[View all projects]({{ base_path }}/projects/)

Honors & Awards
======

- First-Class Outstanding Student Scholarship, Sun Yat-sen University, 2025
- Second-Class Outstanding Student Scholarship, Sun Yat-sen University, 2024
- Second-Class Outstanding Student Scholarship, Sun Yat-sen University, 2023
- Second-Class Outstanding Student Scholarship, Sun Yat-sen University, 2021

Contact
======

I welcome conversations about reinforcement learning, embodied intelligence, and real-world robot deployment. Please feel free to contact me at [zhangyy393@mail2.sysu.edu.cn](mailto:zhangyy393@mail2.sysu.edu.cn).
