---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Reinforcement Learning / Robot Learning Research Engineer  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build reinforcement learning systems end to end: algorithm implementation, simulated environments, experiment design, evaluation, and deployment. My current work focuses on recurrent RL under partial observability, embodied agents, sim-to-real transfer, motion imitation, and search/planning methods such as AlphaZero-style self-play.

## Research / Engineering Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full RL pipeline myself using PyTorch and Isaac Gym: custom recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Trained one onboard Booster T1 policy that combines ball search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Used deployment-oriented actor observations, privileged critic inputs, recurrent state estimation, delayed/noisy ball observations, domain randomization, sparse goal rewards, auxiliary latent prediction, and action-distillation regularization.
- Integrated real-robot state construction from a head-mounted RealSense camera, ball detection, odometry, and compact task observations; accounted for policy, actuator, perception, and ball-dynamics delays.
- Designed simulation and hardware benchmarks for first-goal reliability, repeated-reset continuous play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Worked on sim-to-real transfer across Booster T1 and Unitree G1, including robot assets, collision models, normalized policy interfaces, domain randomization, system identification, evaluation scripts, and hardware deployment.
- Developed simulation-trained locomotion controllers for different morphologies, actuator behavior, robot descriptions, and deployment stacks.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing.
- Built imitation-learning infrastructure for agile humanoid skills using consumer motion capture, ReActor-style retargeting, mocap calibration, Isaac Lab training environments, and custom RL algorithm implementations.

## Additional RL / AI Projects

- Implemented an AlphaZero-style self-play system in Python, including Monte Carlo tree search, neural network training, game storage, and a Gumbel AlphaZero variant for batched search.
- Built `py-chess`, a high-performance C++ chess environment with Python bindings, fast legal-move generation, cached board-state tracking, lookup-based optimizations, and an interface designed for RL self-play experiments.

## Research Interests

Reinforcement learning, robot learning, general physical intelligence, recurrent state estimation, model-based/model-free hybrids, AlphaZero/MuZero-style planning and search, embodied agents, world models, humanoid control, imitation learning, sim-to-real transfer, and evaluation of long-horizon autonomous behavior.

## Technical Skills

**RL and ML:** PPO-style training, recurrent actor-critic methods, asymmetric critics, auxiliary losses, MCTS, self-play, imitation learning, reward design, benchmarking.  
**Robotics:** humanoid locomotion, whole-body control, robot soccer, motion tracking, sim-to-real, system identification, real hardware validation.  
**Simulation:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF, robot asset debugging, custom C++ environments.  
**Software:** Python, C++, PyTorch, ROS/ROS2 workflows, FastAPI, SQLite, Git, Linux.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."
