<h1 align="center">Hi, I'm Ahmed Atif👋</h1>

<p align="center">
Research engineer working on multi-agent reinforcement learning, with a background spanning systems programming, applied ML, robotics, and hardware.
</p>

<p align="center">
  <a href="https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment"><img src="https://img.shields.io/badge/current%20focus-Multi--Agent%20RL-blue" alt="Current focus"></a>
  <a href="https://arxiv.org/abs/2601.17454"><img src="https://img.shields.io/badge/arXiv-2601.17454-b31b1b.svg" alt="arXiv paper"></a>
  <a href="https://provalarous.github.io/PPAGE-Predator-Prey-Archetype-Gridworld-Environment/"><img src="https://img.shields.io/badge/docs-mkdocs-teal.svg" alt="Docs"></a>
</p>

---

### About

I didn't set out to build a multi-agent RL testbed from scratch, I got there by using the existing tools first. An earlier project benchmarked three MARL frameworks (Tianshou, RLlib, MARLlib) against PettingZoo's predator-prey environments and ran tabular Q-learning by hand before reaching for deep RL. That work is the direct ancestor of the project I maintain now: when the existing frameworks made it hard to isolate what was actually causing a result, I built an environment where every layer, dynamics, perception, incentives, learning, is separated by construction, and reproducibility is enforced rather than assumed.

Before MARL, that same instinct for understanding systems from the inside shows up across a Nav2 planner comparison for a TurtleBot3, a from-scratch VGA-timing FPGA game, an analytic raytracer, a lip-to-speech synthesis pipeline wiring together three pretrained models, and a shell implementation with real fork/pipe/signal handling.

### 🔭 Currently building

**[Predator-Prey Archetype Gridworld Environment](https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment)**, a deterministic, modular multi-agent RL testbed built for controlled experimentation and teaching. Six learning baselines (IQL, CQL, MixedTrainer, DQN with Double/Dueling variants, Actor-Critic, A2C), a pluggable observation/reward/action architecture with an immutable core, and a companion research paper studying how embodiment constraints reshape multi-agent coordination.

### 🧰 Tools I reach for

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white" alt="ROS2">
  <img src="https://img.shields.io/badge/Verilog-FPGA-informational" alt="Verilog/FPGA">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
</p>

### 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ProValarous&show_icons=true&hide_border=true" alt="GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ProValarous&layout=compact&hide_border=true" alt="Top languages" height="165">
</p>

---

<p align="center"><sub>Open an issue on a project you find here if something catches your interest.</sub></p>
