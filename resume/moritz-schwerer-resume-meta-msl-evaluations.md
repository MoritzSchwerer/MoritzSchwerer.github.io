---
pagestyle: empty
geometry: margin=0.55in
fontsize: 10pt
---

# Moritz Schwerer

ML Evaluation / Research Engineer | Benchmarks, RL Environments, Robust Behavior  
Email: <m.u.schwerer@gmail.com>  
GitHub: [github.com/MoritzSchwerer](https://github.com/MoritzSchwerer)  
LinkedIn: [linkedin.com/in/moritz-schwerer-b5260726b](https://www.linkedin.com/in/moritz-schwerer-b5260726b)  
**Portfolio: [moritzschwerer.github.io](https://moritzschwerer.github.io)**

## Profile

I build evaluation protocols for learned systems whose behavior must be measurable under uncertainty, distribution shift, noisy perception, and long-horizon degradation. My background is embodied RL rather than LLM-native evaluation, but the overlap is direct: defining behavioral metrics, creating evaluation environments, debugging model failure modes, and turning ambiguous capability gaps into reproducible tests.

## Experience

### Master's Thesis, Hochschule Offenburg | End-to-End RL for Autonomous Humanoid Football

- Implemented the full PyTorch / Isaac Gym RL pipeline: recurrent PPO-style training, asymmetric actor-critic learning, rollout/storage code, reward design, experiment configuration, evaluation, and deployment tooling.
- Built evaluation protocols for model behavior gaps: first-goal reliability, repeated-reset play, alignment quality, kick direction, long-horizon degradation, and controlled-position scoring; validated 26/30 hardware goals.
- Designed policy observations and objectives for partial observability and uncertainty: deployment observations, privileged critics, delayed/noisy perception, sparse rewards, auxiliary latent prediction, and action distillation.
- Debugged failures across perception delay, actuator response, ball dynamics, terrain differences, reward design, observation design, and long-horizon behavior.
- Integrated learned control with real-world perception from a head-mounted RealSense camera, ball detection, odometry, and robot runtime signals.

### Student Research Assistant, Hochschule Offenburg | Humanoid Robot Learning

- Built evaluation scripts and deployment-oriented tooling for sim-to-real transfer across Booster T1 and Unitree G1, including normalized observation/action interfaces, domain randomization, system identification, and hardware validation.
- Developed simulation-trained locomotion controllers that transfer across different robot morphologies, actuator behavior, action spaces, and deployment stacks.
- Built imitation-learning and evaluation infrastructure for whole-body humanoid skills using consumer motion capture, AMASS / SMPL-H data, ReActor-style retargeting, Isaac Lab environments, and custom RL algorithms.
- Contributed to a humanoid football system that placed 2nd in the 3v3 football competition at the World Humanoid Robot Games 2025 in Beijing.

## Additional AI / Perception

- Worked at Robert Bosch GmbH on safety-sensitive LiDAR perception for autonomous driving, including range-view object detection, far-range/tiny-object detection, dataset imbalance, Azure ML workflow improvements, and production-relevant detector analysis.
- Implemented a transformer from scratch in PyTorch, including self-attention and multi-head attention.

## Technical Skills

**Evaluation:** benchmark design, behavioral metrics, failure analysis, long-horizon degradation checks, noisy/delayed observations, distribution shift, robust evaluation protocols.  
**ML / RL:** PyTorch, reinforcement learning, recurrent actor-critic methods, PPO-style training, asymmetric critics, reward design, action distillation, imitation learning.  
**Systems / data:** Python, C++, Azure ML, SQLite, FastAPI, Git, Linux, dataset imbalance analysis, robotics data/state construction.  
**Robotics:** Isaac Gym, Isaac Lab, MuJoCo, sim-to-real transfer, domain randomization, system identification, real hardware validation.

## Education

**M.Sc. Computer Science**, Hochschule Offenburg, Germany  
Thesis: "Learning Robust Goal-Directed Kicking for Real-World Humanoid Robots via End-to-End Reinforcement Learning."  
**B.Sc. Business Information Systems**, Hochschule Offenburg, Germany; thesis at Robert Bosch GmbH on LiDAR perception for autonomous driving.
