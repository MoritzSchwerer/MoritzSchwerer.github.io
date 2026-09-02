---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Robot Learning Research Engineer | RL, Imitation Learning, Deployable Robotics  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build learning-based robot systems from simulation to hardware, with experience in RL, imitation learning, motion data pipelines, whole-body control, sim-to-real transfer, and evaluation under real-world constraints. My strongest fit is studying how learned policies behave inside full robotic systems: perception, planning/control interfaces, action spaces, latency, actuator limits, and deployment reliability.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full RL pipeline using PyTorch and Isaac Gym: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Built a Booster T1 humanoid policy that maps robot state, ball perception, and task observations to autonomous behavior: search, approach, alignment, kicking, reset, and continued play.
- Designed policy inputs and objectives for partial observability and real-world uncertainty: delayed/noisy perception, privileged critics, sparse goal rewards, auxiliary latent prediction, action distillation, and domain randomization.
- Integrated learned control with perception and runtime constraints from a RealSense camera, ball detection, odometry, actuator behavior, perception delay, and ball-dynamics delay.
- Built simulation and hardware evaluation loops for first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Developed simulation-trained locomotion controllers that transfer across Unitree G1 and Booster T1 hardware with different morphologies, actuator behavior, action spaces, robot descriptions, and deployment stacks.
- Built common robot-learning interfaces: normalized observations/actions, robot-specific assets, collision models, low-level PD target control, domain randomization, evaluation scripts, hardware validation, and system identification.
- Built imitation-learning infrastructure for whole-body humanoid skills using consumer motion capture, AMASS / SMPL-H human motion data, ReActor-style retargeting, mocap calibration, Isaac Lab environments, and custom RL algorithms.
- Created deployment-oriented policy evaluation tooling for robot-specific constraints, actuator/latency effects, terrain-dependent dynamics, and real-world behavior debugging.

## Additional AI / Perception

- Worked at Robert Bosch GmbH on LiDAR-based autonomous-driving perception: range-view object detection, far-range/tiny-object detection, dataset imbalance, Azure ML workflow improvements, and safety-sensitive perception evaluation.

## Research Alignment

Deployable robot intelligence, learning-based planning/control, RL, imitation learning, VLA/VLM-aware robotics, hierarchical robotic systems, sim-to-real transfer, real-time constraints, and evaluation of learned behavior inside full systems.

## Technical Skills

**Robot learning:** reinforcement learning, imitation learning, recurrent policies, PPO-style training, asymmetric critics, action distillation, reward design, behavioral evaluation.  
**Robotics systems:** whole-body control, humanoid locomotion, perception-conditioned control, low-level PD target control, normalized observation/action interfaces, system identification, real hardware validation.  
**Simulation / data:** Isaac Gym, Isaac Lab, MuJoCo, MJCF/URDF assets, AMASS / SMPL-H motion data, motion retargeting, domain randomization.  
**Software:** Python, C++, PyTorch, ROS/ROS2 workflows, Azure ML, FastAPI, SQLite, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany; thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
