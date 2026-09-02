---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Humanoid Reinforcement Learning / Robot Learning Engineer  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build humanoid robot learning systems that move from GPU simulation to real hardware: reinforcement learning for robust locomotion and football behaviors, imitation learning for agile whole-body skills, and sensor-integrated deployment on physical robots. Strongest fit: humanoid RL, sim-to-real transfer, behavior cloning / imitation learning, and hardware validation.

## Experience

### Master's Thesis, Hochschule Offenburg | Autonomous Humanoid Football on Booster T1

- Trained and deployed a unified onboard RL controller for autonomous football behavior: search, approach, align, kick, reset, and continue without external motion capture or manually triggered subskills.
- Built the training setup around recurrent asymmetric actor-critic learning, deployment-oriented observations, delayed/noisy ball perception, domain randomization, auxiliary latent prediction, and sparse goal-directed rewards.
- Integrated onboard perception and state construction from a head-mounted RealSense camera, ball detection, odometry, and compact polar task observations; calibrated real-world effects such as ball dynamics on different terrains and policy, actuator, and perception delays.
- Validated on hardware with controlled-position scoring demonstrations, reaching 26/30 goals across close/far and left/middle/right starts.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Developed simulation-trained locomotion controllers that transfer across Unitree G1 and Booster T1 hardware with different morphology, actuator behavior, robot descriptions, and deployment stacks.
- Built common interfaces for multi-robot compatibility: normalized observations/actions, robot-specific assets, low-level PD target control, domain randomization, hardware validation, and real-world identification of actuator, policy, and terrain-dependent dynamics.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing.
- Helped build match behavior around team communication and real-time strategy using only onboard sensing, with no external sensory input beyond each robot's head-mounted RGB camera.
- Developed an imitation-learning framework for agile humanoid skills such as football kicking, dribbling, and locomanipulation using low-cost consumer motion-capture hardware.
- Built tooling around AMASS / SMPL-H motion data, ReActor-style retargeting, mocap calibration, Isaac Lab training environments, custom RL algorithm implementations, and deployment-oriented policy evaluation.

## Technical Skills

**Software:** Python, C++, PyTorch, Linux, Git, ROS/ROS2-style robot interfaces.  
**Simulation and robotics:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, humanoid locomotion, whole-body control, robot football, hardware validation.  
**Robot learning:** reinforcement learning, recurrent policies, PPO-style training, asymmetric actor-critic learning, imitation learning, action distillation, reward design, domain randomization, sim-to-real transfer, system identification, actuator and latency modeling, motion retargeting.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany. Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."
