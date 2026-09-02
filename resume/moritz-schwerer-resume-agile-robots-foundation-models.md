---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Robot Learning Research Engineer | Learning-Based Policies, Sim-to-Real, Embodied AI  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build learning-based robot policies end to end: model/training implementation, simulated environments, experiment design, failure analysis, and real-robot validation. My work focuses on embodied policies under uncertainty, recurrent state estimation, vision-conditioned humanoid behavior, imitation learning, sim-to-real transfer, and representation/objective choices for robust behavior.

## Research / Engineering Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full robot-learning pipeline using PyTorch and Isaac Gym: custom recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Trained one onboard Booster T1 policy that maps robot state, ball perception, and task observations to continuous behavior: search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Designed policy inputs and objectives for partial observability and real-world uncertainty: deployment-oriented actor observations, privileged critic inputs, recurrent state estimation, delayed/noisy ball observations, sparse goal rewards, auxiliary latent prediction, and action-distillation regularization.
- Integrated learned control with real-robot perception and timing constraints from a head-mounted RealSense camera, ball detection, odometry, compact polar task observations, actuator behavior, perception delay, and ball-dynamics delay.
- Analyzed policy behavior and failure modes with benchmarks for first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Worked on sim-to-real transfer across Booster T1 and Unitree G1: robot assets, collision models, normalized observation/action interfaces, domain randomization, system identification, evaluation scripts, and hardware deployment.
- Developed simulation-trained locomotion controllers for different morphologies, actuator behavior, robot descriptions, action spaces, physical constraints, and deployment stacks.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing using onboard robot sensing and real-time team behavior.
- Built imitation-learning infrastructure for agile humanoid skills using consumer motion capture, ReActor-style retargeting, mocap calibration, Isaac Lab training environments, and custom RL algorithm implementations.

## Additional AI / Research

- Implemented an AlphaZero-style self-play system in Python with Monte Carlo tree search, neural network training, game storage, and a Gumbel AlphaZero variant for batched search.

## Research Awareness

Embodied AI, robot learning, vision-language-action systems, multimodal foundation models for robotics, diffusion and transformer policies, world models, imitation learning, RL, sim-to-real transfer, and long-horizon behavioral evaluation.

## Technical Skills

**Robot learning:** learning-based robot policies, imitation learning, reinforcement learning, recurrent actor-critic methods, asymmetric critics, auxiliary losses, reward design, behavioral evaluation, failure analysis.  
**Robotics:** humanoid locomotion, whole-body control, robot soccer, motion tracking, perception-conditioned control, sim-to-real, system identification, real hardware validation.  
**Simulation:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF, robot asset debugging, custom C++ environments.  
**Software:** Python, C++, PyTorch, ROS/ROS2 workflows, FastAPI, SQLite, Git, Linux.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."
