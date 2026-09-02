---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Humanoid Robot Learning Engineer | Whole-Body Control, Sim-to-Real, Loco-Manipulation  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build and deploy learning-based humanoid robot behaviors from simulation to hardware, with experience in whole-body control, motion imitation, perception-conditioned policies, sim-to-real transfer, and real-robot evaluation under timing, actuator, sensing, and terrain constraints. Strongest fit: humanoid robot learning, reliable on-robot testing, rapid experiment iteration, and bridging research ideas into working robotic systems.

## Experience

### Master's Thesis, Hochschule Offenburg | Autonomous Humanoid Football on Booster T1

- Trained and deployed a unified onboard RL controller for autonomous humanoid behavior: search, approach, align, kick, reset, and continue without external motion capture or manually triggered subskills.
- Built the full learning pipeline around recurrent asymmetric actor-critic training, deployment-oriented observations, delayed/noisy ball perception, domain randomization, auxiliary latent prediction, sparse goal-directed rewards, and deployment tooling.
- Integrated learned control with onboard perception and state construction from a head-mounted RealSense camera, ball detection, odometry, compact task observations, low-level control interfaces, and real robot timing constraints.
- Analyzed and debugged system-level behavior across policy, perception, actuator, and environment effects, including ball dynamics on different terrains and policy, actuator, and perception delays.
- Validated on hardware with controlled-position scoring demonstrations, reaching 26/30 goals across close/far and left/middle/right starts.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Developed simulation-trained locomotion controllers that transfer across Unitree G1 and Booster T1 hardware with different morphology, actuator behavior, robot descriptions, action spaces, and deployment stacks.
- Built common interfaces for multi-robot compatibility: normalized observations/actions, robot-specific assets, low-level PD target control, domain randomization, hardware validation, and real-world identification of actuator, policy, and terrain-dependent dynamics.
- Developed imitation-learning infrastructure for agile whole-body humanoid skills such as football kicking, dribbling, and locomanipulation using low-cost consumer motion-capture hardware.
- Built tooling around AMASS / SMPL-H motion data, ReActor-style retargeting, mocap calibration, Isaac Lab training environments, custom RL algorithm implementations, and deployment-oriented policy evaluation.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing using onboard sensing and real-time team behavior.
- Helped build match behavior around team communication and real-time strategy using only onboard sensing, with no external sensory input beyond each robot's head-mounted RGB camera.

## Additional AI / Research

- Implemented an AlphaZero-style self-play system in Python with Monte Carlo tree search, neural network training, game storage, and a Gumbel AlphaZero variant for batched search.
- Built `py-chess`, a high-performance C++ chess environment with Python bindings and an interface designed for RL self-play experiments.

## Technical Skills

**Humanoid robotics:** whole-body control, humanoid locomotion, robot football, loco-manipulation, motion tracking, hardware bring-up support, real hardware validation.  
**Robot learning:** reinforcement learning, recurrent policies, PPO-style training, asymmetric actor-critic learning, imitation learning, action distillation, reward design, sim-to-real transfer, behavior evaluation.  
**Robotics systems:** perception-conditioned control, normalized observation/action interfaces, low-level PD target control, system identification, actuator and latency modeling, deployment debugging.  
**Simulation and software:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, Python, C++, PyTorch, ROS/ROS2-style robot interfaces, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."
