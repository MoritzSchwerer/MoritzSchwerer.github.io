---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Robot Learning Research Engineer | Embodied Agents, Sim-to-Real, Evaluation Tools  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build robot learning systems that connect simulation, policy training, evaluation tooling, and real hardware. My strongest fit is embodied-agent research engineering: PyTorch RL pipelines, robotics infrastructure, sim-to-real transfer, real-robot policy deployment, evaluation protocols, and debugging behavior under noisy perception, latency, and embodiment constraints.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full RL pipeline using PyTorch and Isaac Gym: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Trained one onboard Booster T1 policy that maps robot state, ball perception, and task observations to autonomous behavior: search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Designed policy observations and objectives for partial observability and real-world uncertainty: delayed/noisy perception, privileged critics, sparse rewards, auxiliary latent prediction, action distillation, and domain randomization.
- Integrated learned policies with real-robot runtime constraints from a head-mounted RealSense camera, ball detection, odometry, actuator behavior, perception delay, and ball-dynamics delay.
- Built evaluation protocols for behavior gaps and failure modes: first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Worked across the robot learning stack for Booster T1 and Unitree G1: robot assets, collision models, normalized observation/action interfaces, domain randomization, system identification, evaluation scripts, and deployment.
- Developed simulation-trained locomotion controllers that transfer across robot morphologies, actuator behavior, action spaces, robot descriptions, and deployment stacks.
- Built imitation-learning and evaluation tooling for whole-body humanoid skills using consumer motion capture, AMASS / SMPL-H data, ReActor-style retargeting, mocap calibration, Isaac Lab environments, and custom RL algorithms.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing using onboard sensing and real-time team behavior.

## Additional AI / Perception

- Worked at Robert Bosch GmbH on LiDAR perception for autonomous driving: range-view object detection, far-range and tiny-object detection, dataset imbalance, Azure ML workflow improvements, and safety-sensitive perception evaluation.
- Implemented a transformer from scratch in PyTorch, including self-attention and multi-head attention.

## Technical Skills

**Robot learning:** reinforcement learning, imitation learning, recurrent actor-critic methods, PPO-style training, asymmetric critics, reward design, behavioral evaluation, failure analysis.  
**Robotics systems:** sim-to-real transfer, normalized observation/action interfaces, perception-conditioned control, low-level PD target control, system identification, actuator and latency modeling, real hardware validation.  
**Simulation / data:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, AMASS / SMPL-H motion data, motion retargeting, domain randomization.  
**Software:** Python, C++, PyTorch, ROS/ROS2 workflows, Azure ML, FastAPI, SQLite, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany; thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
