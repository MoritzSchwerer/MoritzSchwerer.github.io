---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Reinforcement Learning Research Engineer | RL Pipelines, Evaluation, Agent Behavior  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build reinforcement learning systems end to end: training code, rollout/storage logic, environments, objectives, experiment configuration, evaluation protocols, and deployment tooling. My current work is robotics-focused, but the core strengths match RL research engineering: fast iteration, clean implementation, reward/objective design, failure analysis, and empirical evaluation of long-horizon agent behavior.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented a complete PyTorch RL pipeline using Isaac Gym: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Trained one onboard Booster T1 policy that combines ball search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Used deployment-oriented actor observations, privileged critic inputs, recurrent state estimation, delayed/noisy ball observations, domain randomization, sparse goal rewards, auxiliary latent prediction, and action distillation.
- Built simulation and hardware benchmarks for first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.
- Debugged policy failures across observation design, reward structure, perception delay, actuator behavior, ball dynamics, terrain differences, and long-horizon degradation.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Developed simulation-trained locomotion controllers that transfer across Unitree G1 and Booster T1 hardware with different morphology, actuator behavior, action spaces, robot descriptions, and deployment stacks.
- Built common interfaces for multi-robot compatibility: normalized observations/actions, robot-specific assets, low-level PD target control, domain randomization, evaluation scripts, hardware validation, and system identification.
- Built imitation-learning infrastructure for whole-body humanoid skills using consumer motion capture, AMASS / SMPL-H motion data, ReActor-style retargeting, mocap calibration, Isaac Lab environments, and custom RL algorithms.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing.

## Additional RL / AI

- Implemented an AlphaZero-style self-play system in Python with Monte Carlo tree search, neural network training, game storage, and a Gumbel AlphaZero variant for batched search.
- Built `py-chess`, a high-performance C++ chess environment with Python bindings and an interface designed for RL self-play experiments.
- Implemented a transformer from scratch in PyTorch, including self-attention and multi-head attention.

## Technical Skills

**RL / ML:** PyTorch, reinforcement learning, recurrent actor-critic methods, PPO-style training, asymmetric critics, auxiliary losses, reward design, MCTS, self-play, behavioral evaluation.  
**RL engineering:** rollout/storage code, experiment configuration, benchmark design, environment design, failure analysis, long-horizon behavior testing, deployment tooling.  
**Robotics:** Isaac Gym, Isaac Lab, MuJoCo, sim-to-real transfer, domain randomization, system identification, real hardware validation.  
**Software:** Python, C++, Azure ML, FastAPI, SQLite, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany; thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
