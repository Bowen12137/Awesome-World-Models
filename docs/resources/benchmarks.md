# Benchmarks & Leaderboards for World Models

Evaluation suites, benchmark tasks, and metrics for comparing world models across driving, robotics, video generation, and multi-agent settings.

---

## 🚗 Driving Benchmarks

| Benchmark | Focus | Resources |
|-----------|-------|-----------|
| **WorldLens** | Full-spectrum evaluation for driving world models | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.10958) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://worldbench.github.io/worldlens) |
| **DrivingGen** | Benchmark for generative video world models in autonomous driving | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.01528) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://drivinggen-bench.github.io/) |
| **NAVSIM** | End-to-end planning benchmark for autonomous driving | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15349) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/autonomousvision/navsim) |
| **nuPlan** | Large-scale planning benchmark with closed-loop simulation | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2106.11810) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.nuscenes.org/nuplan) |

---

## 🤖 Embodied AI & Robotics Benchmarks

| Benchmark | Focus | Resources |
|-----------|-------|-----------|
| **LIBERO** | Knowledge transfer and long-horizon language-conditioned manipulation | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.03310) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Lifelong-Robot-Learning/LIBERO) |
| **CALVIN** | Language-conditioned manipulation benchmark for long-horizon robot tasks | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.03227) [![Website](https://img.shields.io/badge/Website-Link-blue)](http://calvin.cs.uni-freiburg.de/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/mees/calvin) |
| **RoboCasa** | Large-scale everyday manipulation benchmark in realistic simulation | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.02523) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robocasa.ai/) |
| **RoboTwin 2.0** | Bimanual manipulation benchmark with domain randomization and multi-embodiment evaluation | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.18088) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robotwin-platform.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/RoboTwin-Platform/RoboTwin) |

---

## 🎬 Video & World Generation Benchmarks

| Benchmark | Focus | Resources |
|-----------|-------|-----------|
| **WorldScore** | Unified benchmark for world generation quality and controllability | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.00983) |
| **VBench** | Video generation quality evaluation with open-source tooling | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17982) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Vchitect/VBench) |

---

## 👥 Multi-Agent Benchmarks

| Benchmark | Focus | Resources |
|-----------|-------|-----------|
| **Melting Pot** | Generalization-oriented multi-agent RL evaluation suite | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.13746) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/google-deepmind/meltingpot) |

---

## 📏 Common Metrics

- **FVD / FID** — perceptual quality and diversity for generated video rollouts
- **LPIPS** — perceptual similarity between predicted and target frames
- **PSNR / SSIM** — frame-level reconstruction fidelity
- **ADE / FDE / collision rate / closed-loop score** — trajectory and planning quality in driving settings
- **Task success / return / success rate** — downstream control performance in robotics and embodied evaluation
- **Robustness under distribution shift** — generalization across tasks, embodiments, scenes, and environments

---

## 🔗 Benchmark Hubs

- **[Papers with Code](https://paperswithcode.com/)** — benchmark discovery and leaderboard tracking
- **[VBench GitHub](https://github.com/Vchitect/VBench)** — open-source evaluation code for video generation
- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)** — embodied evaluation benchmark and codebase
- **[Melting Pot](https://github.com/google-deepmind/meltingpot)** — multi-agent evaluation suite and environments

---

**Last Updated**: April 2026
