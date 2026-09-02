---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Robotics Simulation / Sim-to-Real Engineer | Policy Evaluation, Real-World Validation  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build simulation-trained robot learning systems and close sim-to-real gaps through domain randomization, system identification, actuator/latency modeling, asset debugging, and real-hardware evaluation. My work is strongest at the interface of simulation realism and downstream policy behavior: defining measurable failure modes, testing policies under noisy sensing and dynamics mismatch, and validating whether simulation improvements translate to real robot performance.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Built an Isaac Gym training setup for a Booster T1 humanoid policy, including recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, and deployment tooling.
- Modeled deployment constraints in training: delayed/noisy ball perception, deployment-oriented actor observations, privileged critic inputs, sparse goal rewards, auxiliary latent prediction, action distillation, and domain randomization.
- Integrated learned control with hardware signals from a head-mounted RealSense camera, ball detection, odometry, compact task observations, actuator behavior, perception delay, and ball-dynamics delay.
- Calibrated real-world effects including ball dynamics on different terrains, policy/action delays, actuator response, and perception latency to improve policy transfer and evaluation quality.
- Built simulation and hardware benchmarks for first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Developed simulation-trained locomotion controllers that transfer across Unitree G1 and Booster T1 hardware with different morphologies, actuator behavior, robot descriptions, action spaces, and deployment stacks.
- Built common interfaces for multi-robot compatibility: normalized observations/actions, robot-specific assets, collision models, low-level PD target control, domain randomization, hardware validation, and real-world system identification.
- Created evaluation tooling for sim-to-real transfer, robot-specific constraints, actuator and latency effects, terrain-dependent dynamics, and real-world behavior debugging.
- Built imitation-learning infrastructure for whole-body humanoid skills using consumer motion capture, AMASS / SMPL-H motion data, ReActor-style retargeting, mocap calibration, Isaac Lab environments, and custom RL algorithms.

## Additional AI / Perception

- Worked at Robert Bosch GmbH on LiDAR-based autonomous-driving perception, including range-view object detection, far-range/tiny-object detection, dataset imbalance, Azure ML workflow improvements, and safety-sensitive perception evaluation.

## Technical Skills

**Simulation / robotics:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, robot asset debugging, domain randomization, system identification, actuator and latency modeling, sim-to-real transfer.  
**Robot learning:** reinforcement learning, imitation learning, recurrent policies, PPO-style training, asymmetric critics, reward design, action distillation, behavioral evaluation.  
**Validation tooling:** real hardware validation, policy failure analysis, benchmark design, controlled-position tests, repeated-reset evaluation, long-horizon behavior checks.  
**Software:** Python, C++, PyTorch, ROS/ROS2 workflows, Azure ML, FastAPI, SQLite, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany; thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
