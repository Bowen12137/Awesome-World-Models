# Tutorials & Courses for World Models

A beginner-friendly learning guide for people who are new to world models and want a clear path into the field.

If you do not know where to start, begin with the **Beginner Journey** below instead of jumping straight into papers or large codebases.

---

## 🌱 Who This Page Is For

This page is for readers who want to answer four questions quickly:

1. **What is a world model?**
2. **What should I read or watch first?**
3. **What should I implement first?**
4. **Which direction should I go next: RL, driving, or robotics?**

The goal is not to list everything. The goal is to give you a safe, high-signal path into the area.

---

## 🚀 Beginner Journey

### Stage 1 — Build intuition

**Goal:** understand what a world model is and why it matters.

| Resource | Why start here? | Format | Resources |
|----------|------------------|--------|-----------|
| **World Models (Ha & Schmidhuber)** | Classic conceptual starting point for latent dynamics, imagination, and agent learning | Tutorial + paper/code | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://worldmodels.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/ctallec/world-models) |
| **A Path Towards Autonomous Machine Intelligence** | Big-picture framing for why predictive world models matter | Talk + paper | [![Video](https://img.shields.io/badge/Video-YouTube-red)](https://www.youtube.com/watch?v=OKkEdTchsiE) [![Paper](https://img.shields.io/badge/Paper-OpenReview-8E44AD.svg)](https://openreview.net/pdf?id=BZ5a1r-kVsf) |

**You should leave this stage able to explain:** latent state, prediction, imagination, and why world models help planning or control.

### Stage 2 — Learn the core loop

**Goal:** understand the standard world-model pipeline used in modern model-based RL and many embodied systems.

| Resource | What you learn | Format | Resources |
|----------|----------------|--------|-----------|
| **CS285: Deep Reinforcement Learning** | Model-based RL foundations behind modern world-model agents | Course | [![Website](https://img.shields.io/badge/Website-Link-blue)](http://rail.eecs.berkeley.edu/deeprlcourse/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/berkeleydeeprlcourse/homework_fall2023) |
| **DreamerV3** | A strong reference line for encoder + dynamics + value/policy training | Project + code | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://danijar.com/project/dreamerv3/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/danijar/dreamerv3) |

**You should leave this stage able to identify:** encoder, latent dynamics, rollout, reconstruction/prediction losses, and how planning/policy learning connects to prediction.

### Stage 3 — Try one hands-on starting point

**Goal:** learn one complete workflow before touching large domain-specific systems.

| Starting Point | Best for | Why it is a good first project | Resources |
|----------------|----------|-------------------------------|-----------|
| **World Models from Scratch** | Absolute beginners | Small, self-contained, historically important | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://worldmodels.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/ctallec/world-models) |
| **DreamerV3 official implementation** | Readers comfortable with RL code | Modern reference implementation used throughout the area | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://danijar.com/project/dreamerv3/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/danijar/dreamerv3) |
| **DreamerV3 PyTorch port** | PyTorch-first learners | Easier if you want the same ideas in a more familiar framework | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/NM512/dreamerv3-torch) |

**Recommendation:** if you are new, start here before trying driving stacks or large robotics training pipelines.

### Stage 4 — Choose a specialization

Once you understand the basic loop, pick one track.

| Track | Start with | Then move to |
|------|------------|--------------|
| **General / Model-Based RL** | DreamerV3 + CS285 | compare latent-state world models and policy-centric systems |
| **Autonomous Driving** | CARLA + driving world-model papers | occupancy/video generation, planning benchmarks, closed-loop evaluation |
| **Embodied AI / Robotics** | CALVIN / LIBERO ecosystem | manipulation, VLA/WAM systems, sim-to-real evaluation |

---

## 🧭 Learning Paths by Goal

### I want conceptual understanding first
Follow this order:
1. World Models project page
2. Yann LeCun's AMI talk/paper
3. DreamerV3 overview
4. Then choose a domain track

### I want to implement something first
Follow this order:
1. World Models from Scratch
2. DreamerV3 official implementation
3. DreamerV3 PyTorch port
4. Then inspect one domain-specific codebase

### I care about autonomous driving
Start here:
- **CARLA** for simulation-based experimentation [![Website](https://img.shields.io/badge/Website-Link-blue)](https://carla.readthedocs.io/)
- **DriveDreamer** for a representative driving world-model codebase [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/JeffWang987/DriveDreamer)
- then move to datasets and benchmarks in [docs/resources/datasets.md](../resources/datasets.md) and [docs/resources/benchmarks.md](../resources/benchmarks.md)

### I care about robotics / embodied AI
Start here:
- **CALVIN** for language-conditioned manipulation [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/mees/calvin)
- **LIBERO** for evaluation and transfer in robot learning [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Lifelong-Robot-Learning/LIBERO)
- then move to embodied world-model papers and WAM/VLA systems in the main README

---

## 📚 Curated Resources by Difficulty

### Beginner
- **World Models** — the best first conceptual entry point
- **A Path Towards Autonomous Machine Intelligence** — big-picture motivation
- **CS285 model-based RL material** — background for the standard learning loop

### Intermediate
- **DreamerV3** — modern reference implementation
- **DriveDreamer** — domain-specific world-model system for driving
- **CALVIN** — practical embodied benchmark/codebase for manipulation

### Advanced
- large-scale driving benchmarks and closed-loop evaluation
- embodied VLA/WAM systems
- multi-domain or foundation-model world models

---

## 🛠️ Hands-On Starting Points

| Resource | Domain | Why it matters | Resources |
|----------|--------|----------------|-----------|
| **DreamerV3** | General / RL | canonical modern world-model training loop | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/danijar/dreamerv3) |
| **DriveDreamer** | Driving | representative video world-model system | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/JeffWang987/DriveDreamer) |
| **CALVIN** | Robotics | practical manipulation benchmark and baseline | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/mees/calvin) |
| **Habitat Lab** | Navigation | good entry point for embodied navigation environments | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/facebookresearch/habitat-lab) |

---

## ⚠️ What to Skip at First

If you are completely new, do **not** start with:

- giant autonomous-driving stacks with many moving parts
- occupancy forecasting papers without first understanding the basic world-model loop
- highly specialized robotics post-training systems
- benchmark tables without intuition for what is actually being measured

A much better order is:
1. concept
2. core loop
3. one small implementation
4. one domain track

---

## 🔗 Next Steps

Once you finish the beginner path:

- see [talks.md](talks.md) for broader talks and keynote material
- see [../resources/datasets.md](../resources/datasets.md) for datasets by domain
- see [../resources/benchmarks.md](../resources/benchmarks.md) for evaluation suites and metrics
- see [../research/taxonomy.md](../research/taxonomy.md) to understand how the field is organized in this repository

---

**Last Updated**: April 2026
