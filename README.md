<h1 align="center">Hi, I'm Ahmed Atif 👋</h1>

<p align="center">
Research engineer working on multi-agent reinforcement learning, with a background spanning systems programming, applied ML, robotics, and hardware.
</p>

<p align="center">
  <a href="https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment"><img src="https://img.shields.io/badge/current%20focus-Multi--Agent%20RL-blue" alt="Current focus"></a>
  <a href="https://arxiv.org/abs/2601.17454"><img src="https://img.shields.io/badge/arXiv-2601.17454-b31b1b.svg" alt="arXiv paper"></a>
  <a href="https://provalarous.github.io/PPAGE-Predator-Prey-Archetype-Gridworld-Environment/"><img src="https://img.shields.io/badge/docs-mkdocs-teal.svg" alt="Docs"></a>
  <a href="https://orcid.org/0009-0006-1380-5483"><img src="https://img.shields.io/badge/ORCID-0009--0006--1380--5483-a6ce39?logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://www.linkedin.com/in/ahmedatif256/"><img src="https://img.shields.io/badge/LinkedIn-ahmedatif256-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://komarev.com/ghpvc/?username=ProValarous&label=profile%20views&color=6e5494&style=flat" alt="Profile views">
</p>

---

### About

I didn't set out to build a multi-agent RL testbed from scratch — I got there by using the existing tools first. An earlier project benchmarked three MARL frameworks (Tianshou, RLlib, MARLlib) against PettingZoo's predator-prey environments and ran tabular Q-learning by hand before reaching for deep RL. That work is the direct ancestor of the project I maintain now: when the existing frameworks made it hard to isolate what was actually causing a result, I built an environment where every layer — dynamics, perception, incentives, learning — is separated by construction, and reproducibility is enforced rather than assumed.

Before MARL, that same instinct for understanding systems from the inside shows up across a Nav2 planner comparison for a TurtleBot3, a from-scratch VGA-timing FPGA game, an analytic raytracer, a lip-to-speech synthesis pipeline wiring together three pretrained models, and a shell implementation with real fork/pipe/signal handling.

### 🔭 Currently building

**[Predator-Prey Archetype Gridworld Environment](https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment)** — a deterministic, modular multi-agent RL testbed built for controlled experimentation and teaching. Six learning baselines (IQL, CQL, MixedTrainer, DQN with Double/Dueling variants, Actor-Critic, A2C), a pluggable observation/reward/action architecture with an immutable core, and a companion research paper studying how embodiment constraints reshape multi-agent coordination.

<p align="center">
  <a href="https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=ProValarous&repo=PPAGE-Predator-Prey-Archetype-Gridworld-Environment&theme=github_dark&hide_border=true&show_owner=false">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=ProValarous&repo=PPAGE-Predator-Prey-Archetype-Gridworld-Environment&theme=default&hide_border=true&show_owner=false" alt="PPAGE repository card">
    </picture>
  </a>
</p>

### 🗂️ Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| [PPAGE](https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment) | Deterministic modular MARL testbed, six baselines, companion paper | Python, PyTorch |
| [ROS2 Comparative Planner Analysis](https://github.com/ProValarous/ROS2-Comparative-Planner-Analysis) | Nav2 global/local planner comparison on a TurtleBot3 | ROS 2, Python |
| [Chrome T-Rex on FPGA](https://github.com/ProValarous/Chrome-T-Rex-Game-Using-EMG) | VGA-timing game driven by EMG input, built from scratch in HDL | Verilog, FPGA |
| MARL framework benchmark <!-- TODO: add repo link --> | Tianshou / RLlib / MARLlib against PettingZoo, plus hand-rolled tabular Q-learning | Python |
| Lip-to-speech pipeline <!-- TODO: add repo link --> | Three pretrained models wired into one inference path | Python, PyTorch |
| Analytic raytracer <!-- TODO: add repo link --> | Closed-form intersection renderer, no external graphics libs | C++ |
| Unix shell <!-- TODO: add repo link --> | Real fork/exec, pipes, redirection, signal handling | C |

### 🧰 Tools I reach for

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat&logo=ros&logoColor=white" alt="ROS 2">
  <img src="https://img.shields.io/badge/Verilog-FPGA-informational" alt="Verilog/FPGA">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux">
</p>

---

### 📊 Metrics

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=ProValarous&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=github_dark&custom_title=GitHub%20Stats">
    <img height="170" src="https://github-readme-stats.vercel.app/api?username=ProValarous&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=default&custom_title=GitHub%20Stats" alt="GitHub stats">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=ProValarous&layout=compact&langs_count=8&hide=html,css,scss&exclude_repo=DBMS_Project,WareHouse-Managment-System&hide_border=true&theme=github_dark">
    <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ProValarous&layout=compact&langs_count=8&hide=html,css,scss&exclude_repo=DBMS_Project,WareHouse-Managment-System&hide_border=true&theme=default" alt="Top languages">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=ProValarous&hide_border=true&theme=github-dark-blue">
    <img src="https://streak-stats.demolab.com?user=ProValarous&hide_border=true&theme=default" alt="Contribution streak">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=ProValarous&theme=github-compact&hide_border=true&area=true&radius=8">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=ProValarous&theme=github-light&hide_border=true&area=true&radius=8" alt="Contribution activity over the last year">
  </picture>
</p>

<!-- Optional, uncomment if you want it. Reads as gamified on a research profile.
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ProValarous&theme=flat&no-frame=true&no-bg=true&column=7&margin-w=6" alt="Trophies">
</p>
-->

### 📈 Project reach

Live counters, so these update themselves as the work gets picked up.

<p align="center">
  <a href="https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment/stargazers"><img src="https://img.shields.io/github/stars/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment?style=flat&logo=github&label=PPAGE%20stars" alt="PPAGE stars"></a>
  <a href="https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment/forks"><img src="https://img.shields.io/github/forks/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment?style=flat&logo=github&label=forks" alt="PPAGE forks"></a>
  <a href="https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment/issues"><img src="https://img.shields.io/github/issues/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment?style=flat&label=open%20issues" alt="Open issues"></a>
  <a href="https://github.com/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment/commits"><img src="https://img.shields.io/github/last-commit/ProValarous/PPAGE-Predator-Prey-Archetype-Gridworld-Environment?style=flat&label=last%20commit" alt="Last commit"></a>
  <a href="https://github.com/ProValarous?tab=followers"><img src="https://img.shields.io/github/followers/ProValarous?style=flat&logo=github&label=followers" alt="Followers"></a>
</p>

---

<p align="center"><sub>Open an issue on a project you find here if something catches your interest.</sub></p>
