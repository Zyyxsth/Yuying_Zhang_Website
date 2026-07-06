---
layout: archive
title: "Projects & Experience"
permalink: /projects/
author_profile: true
lang: en
alternate_url: /zh/projects/
---

Humanoid High-Dynamic Motion and Boxing Locomotion
======

**EngineAI · May 2026–Present**

Developed high-dynamic motion skills for the T800 humanoid robot, including sweeping kicks and aerial spinning kicks, based on BeyondMimic. Trained AMP-based boxing-style omnidirectional locomotion and improved posture support, style clarity, reward stability, and directional consistency. Policies were deployed successfully in MuJoCo and on real hardware.

Constrained RL for Wheeled-Legged Stair Climbing
======

**DirectDrive Technology (DDT) · Oct. 2025–Dec. 2025**

Designed autonomous stair-climbing control for the D1 wheeled-legged robot under hybrid contact dynamics and strict safety constraints.

- Developed a joint-level hard-constrained policy optimization method based on NP3O.
- Added Barlow Twins self-supervision to privileged learning for stronger representations and more robust Sim-to-Real transfer.
- Completed simulation training, real-world deployment, ablation studies, and comparative experiments.

Threat-Aware UAV Dodging
======

**First author · Dec. 2024–Sep. 2025**

Developed a real-time UAV threat perception and dodging system using only an onboard RGB-D camera. The system anticipates human-thrown projectiles from body motion, predicts projectile trajectories before release, and optimizes uncertainty-aware evasive maneuvers.

- Built the perception pipeline from human pose estimation and 3D keypoint recovery to physics-based projectile prediction.
- Integrated spatiotemporal uncertainty into threat assessment and trajectory optimization.
- Achieved a 6 m detection range, 26.4 ms CPU-only perception latency, and a 96.67% dodging success rate in real-world tests.

[Project page](https://threat-aware-dodging.github.io/) · [Paper](https://doi.org/10.1109/LRA.2025.3641149) · [arXiv](https://arxiv.org/abs/2511.22847)

Autonomous Inspection for Nuclear Power Plant Environments
======

**Planning and Control Lead · Apr. 2025–Aug. 2025**

Built the mapping, planning, control, and task state-machine modules for a wheeled-legged robot inspection system in complex nuclear power plant environments. The system combined LiDAR-based localization, local grid mapping, dynamically feasible trajectory optimization, online replanning, MPC tracking, target detection, and remote communication.
