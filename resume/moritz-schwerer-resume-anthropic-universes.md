---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Reinforcement Learning Research Engineer | Training Environments, Evaluation, Robust Agents  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build RL systems end to end: training environments, policy implementation, experiment tooling, evaluation protocols, and failure analysis for agents operating under uncertainty. My background is embodied rather than LLM-native, but the transferable core is strong: designing environments and objectives, testing long-horizon behavior, debugging failures, and turning ambiguous behavior gaps into concrete evaluations.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full RL pipeline using PyTorch and Isaac Gym: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Built a training environment for an autonomous Booster T1 policy combining search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Designed objectives and observations for partial observability and real-world uncertainty: delayed/noisy perception, privileged critics, sparse goal rewards, auxiliary latent prediction, recurrent state estimation, and action distillation.
- Built rigorous evaluations for first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.
- Debugged failures across policy behavior, perception latency, actuator response, ball dynamics, terrain differences, and long-horizon degradation.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Worked across RL environments, robot assets, collision models, normalized observation/action interfaces, domain randomization, system identification, evaluation scripts, and hardware deployment.
- Developed simulation-trained locomotion controllers that transfer across Booster T1 and Unitree G1 with different morphologies, actuator behavior, action spaces, and deployment stacks.
- Built imitation-learning and evaluation infrastructure for whole-body humanoid skills using consumer motion capture, AMASS / SMPL-H data, ReActor-style retargeting, Isaac Lab environments, and custom RL algorithms.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing.

## Additional AI / Perception

- Implemented an AlphaZero-style self-play system in Python with Monte Carlo tree search, neural network training, game storage, and a Gumbel AlphaZero variant for batched search.
- Worked at Robert Bosch GmbH on safety-sensitive LiDAR perception for autonomous driving, including range-view detection, far-range/tiny-object detection, dataset imbalance, and Azure ML workflow improvements.

## Technical Skills

**RL systems:** PyTorch, PPO-style training, recurrent actor-critic methods, asymmetric critics, auxiliary losses, reward design, self-play, MCTS, behavioral evaluation.  
**Environments / evaluation:** training environment design, long-horizon behavior testing, failure analysis, benchmark design, noisy/delayed observations, distribution shift, sim-to-real transfer.  
**Robotics:** Isaac Gym, Isaac Lab, MuJoCo, domain randomization, system identification, real hardware validation, normalized observation/action interfaces.  
**Software:** Python, C++, Azure ML, FastAPI, SQLite, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany; thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
