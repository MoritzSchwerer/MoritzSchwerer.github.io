---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Robot Learning Research Engineer | Real-Robot Policies, Sim-to-Real, Evaluation  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build robot learning systems end to end: policy/training implementation, simulated environments, data and observation design, experiment tooling, failure analysis, and real-hardware validation. My work focuses on embodied policies under uncertainty, imitation learning, sim-to-real transfer, motion data pipelines, and fast evaluation loops for reliable autonomous behavior.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full RL pipeline using PyTorch and Isaac Gym: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Trained one onboard Booster T1 policy that maps robot state, ball perception, and task observations to autonomous behavior: search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Designed policy inputs, objectives, and training assumptions for partial observability and real-world uncertainty: deployment-oriented actor observations, privileged critic inputs, delayed/noisy ball observations, sparse goal rewards, auxiliary latent prediction, and action-distillation regularization.
- Integrated learned control with real-robot perception and runtime constraints from a head-mounted RealSense camera, ball detection, odometry, compact task observations, actuator behavior, perception delay, and ball-dynamics delay.
- Built simulation and hardware evaluation loops for first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Worked across the robot learning stack for Booster T1 and Unitree G1: robot assets, collision models, normalized observation/action interfaces, domain randomization, system identification, evaluation scripts, and deployment.
- Developed simulation-trained locomotion controllers that transfer across different robot morphologies, actuator behavior, action spaces, and deployment stacks.
- Built imitation-learning infrastructure for whole-body humanoid skills using consumer motion capture, AMASS / SMPL-H motion data, ReActor-style retargeting, mocap calibration, Isaac Lab environments, and custom RL algorithms.
- Created deployment-oriented policy evaluation tooling for sim-to-real transfer, robot-specific constraints, actuator and latency effects, and real-world behavior debugging.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing using onboard sensing and real-time team behavior.

## Research Alignment

General-purpose physical intelligence, robot foundation models, vision-language-action policies, robot pretraining/adaptation, world models, imitation learning, RL, sim-to-real transfer, and rigorous policy-failure evaluation.

## Technical Skills

**Robot learning:** RL policies, imitation learning, recurrent actor-critic methods, asymmetric critics, auxiliary losses, action distillation, reward design, behavioral evaluation.  
**Robotics systems:** perception-conditioned control, normalized observation/action interfaces, low-level PD target control, system identification, actuator and latency modeling, deployment debugging.  
**Simulation and data:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, AMASS / SMPL-H motion data, motion retargeting, domain randomization.  
**Software:** Python, C++, PyTorch, ROS/ROS2 workflows, FastAPI, SQLite, Git, Linux.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."
