---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

Reinforcement Learning / Robust AI Systems Research Engineer  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build and evaluate learning-based systems whose behavior must remain reliable under uncertainty, noisy perception, latency, distribution shift, and long-horizon degradation. My strongest fit is not direct LLM post-training, but robust model behavior: reward/objective design, RL pipelines, behavioral evaluation, failure analysis, and safety-sensitive perception experience.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full RL pipeline using PyTorch and Isaac Gym: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Trained one onboard Booster T1 policy that maps robot state, ball perception, and task observations to autonomous behavior: search, approach, alignment, kicking, reset, and continued play without external motion capture or manually triggered subskills.
- Designed policy inputs, objectives, and training assumptions for partial observability and real-world uncertainty: deployment observations, privileged critics, delayed/noisy perception, sparse rewards, auxiliary latent prediction, and action distillation.
- Built evaluation protocols for behavior gaps and failure modes: first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.
- Integrated learned control with real-world perception/runtime constraints from a head-mounted RealSense camera, ball detection, odometry, actuator behavior, perception delay, and ball-dynamics delay.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Worked across the robot learning stack for Booster T1 and Unitree G1: robot assets, normalized observation/action interfaces, domain randomization, system identification, evaluation scripts, and deployment.
- Developed simulation-trained locomotion controllers that transfer across robot morphologies, actuator behavior, action spaces, and deployment stacks.
- Built imitation-learning and evaluation tooling for whole-body skills using consumer motion capture, AMASS / SMPL-H data, ReActor-style retargeting, Isaac Lab environments, custom RL algorithms, and real-world behavior debugging.

### Robert Bosch GmbH | Autonomous Driving Alliance

- Worked as an AI Research Engineer working student on LiDAR perception for autonomous driving, including range-view object detection and Azure ML workflow improvements for faster research iteration.
- Evaluated and optimized state-of-the-art LiDAR approaches for far-range detection, tiny-object detection, scenario-dependent performance, dataset imbalance, and safety-sensitive autonomous-driving evaluation.
- Identified range-view detector improvements relevant to a production perception system.

## Research Alignment

Gemini safety, model behavior evaluation, reward/objective design, RL fine-tuning, adversarial robustness, safety-sensitive perception, dataset imbalance, fairness, distribution shift, and behavior-gap evaluation.

## Technical Skills

**ML / RL:** PyTorch, reinforcement learning, recurrent actor-critic methods, PPO-style training, asymmetric critics, reward design, behavioral evaluation, transformer implementation.  
**Robust AI systems:** safety-sensitive perception, LiDAR object detection, dataset imbalance, long-horizon degradation, noisy/delayed observations, distribution shift.  
**Robotics / software:** sim-to-real transfer, domain randomization, system identification, real hardware validation, Isaac Gym, Isaac Lab, MuJoCo, Python, C++, Azure ML, Linux, Git.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany. Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany. Thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
