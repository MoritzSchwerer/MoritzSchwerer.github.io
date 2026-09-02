---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Robotics Software / Robot Learning Engineer | Evaluation, Data, Control Interfaces  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build software around learned robot policies: simulation environments, normalized observation/action interfaces, data and state construction, evaluation tooling, deployment scripts, and real-hardware validation. My work connects research policies to physical robot constraints across sensing, timing, control interfaces, hardware differences, and behavior evaluation.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented a full PyTorch / Isaac Gym RL pipeline: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, configuration, evaluation, and deployment tooling.
- Built onboard state construction for a Booster T1 humanoid from RealSense camera input, ball detection, odometry, compact task observations, and robot runtime signals.
- Trained one deployed policy that combines search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Designed evaluation and quality checks for first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.
- Debugged system-level behavior across policy outputs, perception delays, actuator behavior, ball dynamics, terrain differences, and robot timing constraints.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Built common software interfaces for Booster T1 and Unitree G1: normalized observations/actions, robot-specific assets, low-level PD target control, domain randomization, evaluation scripts, and deployment workflows.
- Developed simulation-trained locomotion controllers that transfer across robot morphologies, actuator behavior, robot descriptions, action spaces, and deployment stacks.
- Built imitation-learning infrastructure using consumer motion capture, AMASS / SMPL-H motion data, ReActor-style retargeting, mocap calibration, Isaac Lab environments, custom RL algorithms, and deployment-oriented policy evaluation.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing using onboard sensing and real-time team behavior.

## Additional AI / Perception

- Worked at Robert Bosch GmbH on LiDAR perception for autonomous driving: range-view object detection, far-range and tiny-object detection, dataset imbalance, Azure ML workflow improvements, and safety-sensitive perception evaluation.
- Built `py-chess`, a high-performance C++ environment with Python bindings for RL self-play experiments.

## Technical Skills

**Robotics software:** state construction, observation/action interfaces, low-level PD target control, deployment scripts, evaluation tooling, real hardware validation, ROS/ROS2 workflows.  
**Robot learning:** reinforcement learning, imitation learning, recurrent policies, PPO-style training, asymmetric critics, reward design, action distillation, behavioral evaluation.  
**Simulation / data:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, AMASS / SMPL-H motion data, motion retargeting, domain randomization.  
**Software:** Python, C++, PyTorch, Azure ML, FastAPI, SQLite, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany; thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
