---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Humanoid Reinforcement Learning Engineer | Whole-Body Control, Sim-to-Real, Policy Deployment  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build humanoid robot learning systems that move from GPU simulation to real hardware: RL for robust locomotion and autonomous football behavior, imitation learning for agile whole-body skills, and deployment-oriented evaluation on physical robots. Strongest fit: humanoid RL, whole-body policy training, sim-to-real transfer, motion imitation, hardware validation, and debugging learned behavior under real robot constraints.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full RL pipeline using PyTorch and Isaac Gym: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Trained and deployed one onboard Booster T1 policy for autonomous football behavior: search, approach, align, kick, reset, and continue without external motion capture or manually triggered subskills.
- Designed deployment-oriented observations and objectives for partial observability and real-world uncertainty: delayed/noisy perception, privileged critics, sparse rewards, auxiliary latent prediction, action distillation, and domain randomization.
- Integrated learned control with onboard sensing from a RealSense camera, ball detection, odometry, compact task observations, low-level control interfaces, actuator behavior, perception delay, and ball-dynamics delay.
- Validated on hardware with controlled-position scoring demonstrations, reaching 26/30 goals across close/far and left/middle/right starts; also evaluated repeated-reset play and long-horizon degradation.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Developed simulation-trained locomotion controllers that transfer across Unitree G1 and Booster T1 hardware with different morphology, actuator behavior, action spaces, robot descriptions, and deployment stacks.
- Built common interfaces for multi-robot compatibility: normalized observations/actions, robot-specific assets, low-level PD target control, domain randomization, hardware validation, and real-world identification of actuator, policy, and terrain-dependent dynamics.
- Developed imitation-learning infrastructure for agile whole-body humanoid skills such as football kicking, dribbling, and locomanipulation using low-cost consumer motion-capture hardware.
- Built tooling around AMASS / SMPL-H motion data, ReActor-style retargeting, mocap calibration, Isaac Lab environments, custom RL algorithm implementations, and deployment-oriented policy evaluation.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing.

## Additional AI / Perception

- Worked at Robert Bosch GmbH on LiDAR-based autonomous-driving perception, including range-view object detection, far-range/tiny-object detection, dataset imbalance, Azure ML workflow improvements, and safety-sensitive perception evaluation.

## Technical Skills

**Humanoid RL:** reinforcement learning, recurrent policies, PPO-style training, asymmetric actor-critic learning, reward design, action distillation, behavioral evaluation, hardware deployment.  
**Robotics:** humanoid locomotion, whole-body control, low-level PD target control, perception-conditioned control, sim-to-real transfer, system identification, actuator and latency modeling.  
**Simulation / data:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, AMASS / SMPL-H motion data, ReActor-style retargeting, domain randomization.  
**Software:** Python, C++, PyTorch, ROS/ROS2 workflows, Azure ML, FastAPI, SQLite, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany; thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
