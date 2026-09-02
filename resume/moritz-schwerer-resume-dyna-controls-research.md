---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Humanoid Robot Learning Engineer | Whole-Body Control, Sim-to-Real, Learning-Based Control  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build and deploy learning-based humanoid controllers from simulation to real hardware, with experience in whole-body behavior, low-level PD target control, actuator and latency modeling, system identification, motion imitation, and hardware validation. Strongest fit: RL/IL-to-real integration, sim-to-real debugging, controller evaluation, and connecting learned policies to robot dynamics, sensing, and physical constraints.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full RL control pipeline using PyTorch and Isaac Gym: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Trained one onboard Booster T1 controller that maps robot state, ball perception, and task observations to dynamic humanoid behavior: search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Designed controller inputs and objectives for partial observability and real-world uncertainty: deployment-oriented actor observations, privileged critic inputs, delayed/noisy ball observations, sparse goal rewards, auxiliary latent prediction, and action-distillation regularization.
- Integrated learned control with real-robot perception and runtime constraints from a head-mounted RealSense camera, ball detection, odometry, compact task observations, low-level control interfaces, actuator behavior, perception delay, and ball-dynamics delay.
- Built simulation and hardware benchmarks for first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Developed simulation-trained locomotion controllers that transfer across Unitree G1 and Booster T1 hardware with different morphologies, actuator behavior, robot descriptions, action spaces, and deployment stacks.
- Built common control interfaces for multi-robot compatibility: normalized observations/actions, robot-specific assets, low-level PD target control, domain randomization, hardware validation, and real-world identification of actuator, policy, and terrain-dependent dynamics.
- Developed imitation-learning infrastructure for agile whole-body humanoid skills such as football kicking, dribbling, and locomanipulation using low-cost consumer motion-capture hardware.
- Built tooling around AMASS / SMPL-H motion data, ReActor-style retargeting, mocap calibration, Isaac Lab training environments, custom RL algorithm implementations, and deployment-oriented policy evaluation.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing using onboard sensing and real-time team behavior.

## Controls / Research Alignment

Learning-based control, whole-body humanoid behavior, sim-to-real transfer, actuator and latency modeling, system identification, high-fidelity simulation, controller benchmarking, hardware deployment, imitation learning, reinforcement learning, and reliable contact-rich robot behavior.

## Technical Skills

**Controls and robotics:** humanoid locomotion, whole-body control, low-level PD target control, normalized observation/action interfaces, actuator and latency modeling, system identification, hardware validation.  
**Robot learning:** reinforcement learning, imitation learning, recurrent policies, PPO-style training, asymmetric actor-critic learning, action distillation, reward design, behavioral evaluation.  
**Simulation and motion data:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, AMASS / SMPL-H motion data, ReActor-style retargeting, domain randomization.  
**Software:** Python, C++, PyTorch, ROS/ROS2-style robot interfaces, Linux, Git, FastAPI, SQLite.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."
