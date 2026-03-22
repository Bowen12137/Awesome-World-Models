<div align="center">

# 🌍 Awesome World Models

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Papers](https://img.shields.io/badge/papers-489-blue)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**The Most Comprehensive Collection of World Models Research**

**Awesome Generative World Models: Video, 3D, Robotics & Driving**

*Spanning Video Generation, 3D/4D Modeling, Autonomous Driving, Embodied AI, and Beyond*

</div>



## 🌳 World Models Evolutionary Tree

<p align="center">
  <img src="assets/images/tree.png" width="100%">
</p>



## 🔥 News & Updates

- **[2026-03-06]** 🎉 Repository launched! Unified collection of 489 papers from four major World Models repositories
- **[2026-03-06]** 🆕 Added 11 latest papers from arXiv 2026 (LaST-VLA, ResWorld, DriveWorld-VLA, etc.)
- **[2026-03-06]** 📊 Added comprehensive statistics and visualizations: 74 starred papers, 195 with code
- **[2026-03-06]** 🗂️ Introduced dual-dimension taxonomy: Paradigm (VideoGen/OccGen/LiDARGen) + Application domains
- **[2026-03-06]** 🤖 Integrated learning resources: talks, courses, tutorials, and datasets

---

## 📖 Table of Contents

- [💡 What are World Models?](#-what-are-world-models)
- [🗺️ Taxonomy](#️-taxonomy)
- [📚 Research](#-research)
  - [Surveys & Reviews](#surveys--reviews)
  - [Papers by Paradigm](#papers-by-paradigm)
    - [🎬 VideoGen: Video-based World Models](#-videogen-video-based-world-models)
    - [🧊 OccGen: Occupancy-based World Models](#-occgen-occupancy-based-world-models)
    - [📡 LiDARGen: LiDAR-based World Models](#-lidargen-lidar-based-world-models)
  - [Papers by Application](#papers-by-application)
    - [🚗 Autonomous Driving](#-autonomous-driving)
    - [🤖 Embodied AI & Robotics](#-embodied-ai--robotics)
    - [🎮 Game Simulation & XR](#-game-simulation--xr)
    - [🔬 Scientific Applications](#-scientific-applications)
  - [💡 Theory & Explainability](#-theory--explainability)
  - [🏢 Industry Reports](#-industry-reports)
- [🎓 Learning Resources](#-learning-resources)
  - [📺 Talks & Presentations](#-talks--presentations)
  - [🎓 Courses & Tutorials](#-courses--tutorials)
- [🔧 Practical Resources](#-practical-resources)
  - [📊 Datasets](#-datasets)
  - [🎯 Benchmarks & Leaderboards](#-benchmarks--leaderboards)
  - [🛠️ Tools & Libraries](#️-tools--libraries)
- [🌐 Community](#-community)
  - [🏆 Workshops & Challenges](#-workshops--challenges)
  - [👥 Research Groups](#-research-groups)
- [🤝 Contributing](#-contributing)
- [📜 Citation](#-citation)
- [⭐ Star History](#-star-history)

---

## 💡 What are World Models?

**World Models** are AI systems that learn internal representations of their environment to predict future states, simulate scenarios, and enable intelligent decision-making. They bridge perception and action by building a mental model of how the world works.

### Key Concepts

- **Predictive Modeling**: Learning to forecast future observations from current state and actions
- **Latent Representations**: Compressing high-dimensional sensory data into meaningful internal states
- **Simulation**: Generating synthetic experiences for planning, training, and evaluation
- **Generalization**: Transferring learned world knowledge to new scenarios and tasks

### Why World Models Matter

1. **Data Efficiency**: Learn from fewer real-world interactions by leveraging simulated experience
2. **Safety**: Test dangerous scenarios in simulation before deployment
3. **Interpretability**: Explicit world representations enable better understanding of AI decisions
4. **Generalization**: Transfer knowledge across tasks and domains
5. **Planning**: Enable look-ahead reasoning for complex decision-making

---

## 🗺️ Taxonomy

This repository organizes world models research along **two complementary dimensions**:

### Dimension 1: Representation Paradigms

How world models represent and generate environmental states:

- **🎬 VideoGen**: Video-based representations using pixel-space generation
  - Leverages powerful video generation models (diffusion, transformers)
  - Natural for camera-based perception systems
  - Examples: Genie, GAIA-1, DriveDreamer

- **🧊 OccGen**: Occupancy-based 3D representations
  - Explicit 3D spatial structure using voxel grids or occupancy fields
  - Efficient for 3D reasoning and planning
  - Examples: OccWorld, GaussianWorld, UniScene

- **📡 LiDARGen**: LiDAR-based point cloud generation
  - Direct modeling of 3D sensor data
  - Preserves geometric precision
  - Examples: LiDARGen, DynamicCity, LiSTAR

### Dimension 2: Application Domains

Where world models are applied:

- **🚗 Autonomous Driving**: Scene prediction, planning, and simulation for self-driving vehicles
- **🤖 Embodied AI & Robotics**: Manipulation, navigation, and interaction in physical environments
- **🎮 Game Simulation & XR**: Procedural content generation and interactive experiences
- **🔬 Scientific Applications**: Physics simulation, molecular dynamics, climate modeling

> 📖 For detailed taxonomy explanation, see [docs/research/taxonomy.md](docs/research/taxonomy.md)

---

## 📚 Research

### Surveys & Reviews

Comprehensive surveys and review papers on world models:

| Title | Venue | Resources |
|-------|-------|-----------|
| ⭐ **The Role of World Models in Shaping Autonomous Driving: A Comprehensive Survey** | `arXiv 25.02` | [![arXiv](https://img.shields.io/badge/arXiv-2502.10498-b31b1b.svg)](https://arxiv.org/abs/2502.10498) |
| **Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI** | `TMECH 25` | [![arXiv](https://img.shields.io/badge/arXiv-2407.06886-b31b1b.svg)](https://arxiv.org/abs/2407.06886) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List) |
| **3D and 4D World Modeling: A Survey** | `arXiv 25.09` | [![arXiv](https://img.shields.io/badge/arXiv-2509.07996-b31b1b.svg)](https://arxiv.org/abs/2509.07996) |
| **A Comprehensive Survey on World Models for Embodied AI** | `arXiv 25.10` | [![arXiv](https://img.shields.io/badge/arXiv-2510.16732-b31b1b.svg)](https://arxiv.org/abs/2510.16732) |
| **A Step Toward World Models: A Survey on Robotic Manipulation** | `arXiv 25.11` | [![arXiv](https://img.shields.io/badge/arXiv-2511.02097-b31b1b.svg)](https://arxiv.org/abs/2511.02097) |
| **A Survey of Embodied World Models** | `25.09` | [![Paper](https://img.shields.io/badge/Paper-Link-blue)](https://www.researchgate.net/publication/395713824_A_Survey_of_Embodied_World_Models) |
| **A Survey on Future Physical World Generation for Autonomous Driving** | `MMAsia 25` | [![Paper](https://img.shields.io/badge/Paper-Link-blue)](https://dl.acm.org/doi/full/10.1145/3769748.3773345) |
| **The Safety Challenge of World Models for Embodied AI Agents: A Review** | `arXiv 25.10` | [![arXiv](https://img.shields.io/badge/arXiv-2510.05865-b31b1b.svg)](https://arxiv.org/abs/2510.05865) |
| **Progressive Robustness-Aware World Models in Autonomous Driving: A Review and Outlook** | `techrXiv 25.11` | [![Paper](https://img.shields.io/badge/Paper-Link-blue)](https://doi.org/10.36227/techrxiv.176523308.84756413/v1) |
| ⭐ **A Path Towards Autonomous Machine Intelligence** (Yann LeCun) | `OpenReview` | [![OpenReview](https://img.shields.io/badge/OpenReview-Paper-8E44AD.svg)](https://openreview.net/pdf?id=BZ5a1r-kVsf) [![Video](https://img.shields.io/badge/Video-YouTube-red)](https://www.youtube.com/watch?v=OKkEdTchsiE) |

> 📖 For complete list of surveys, see [docs/research/surveys.md](docs/research/surveys.md)

---

### Papers by Paradigm

#### 🎬 VideoGen: Video-based World Models

Video-based world models generate future frames in pixel space, leveraging powerful video generation architectures.

**Key Papers:**


#### 🚗 Autonomous Driving Papers

| Paper | Venue | Resources |
|-------|-------|-----------|
| ⭐ **LaST-VLA: Latent Spatio-Temporal VLA for Autonomous Driving** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2603.01928-b31b1b.svg)](https://arxiv.org/abs/2603.01928) |
| ⭐ **Hyper Diffusion Planner: End-to-End Autonomous Driving with Real-Vehicle Deployment** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.22801-b31b1b.svg)](https://arxiv.org/abs/2602.22801) |
| ⭐ **ResWorld: Temporal Residual World Model for Dynamic Object Modeling** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.10884-b31b1b.svg)](https://arxiv.org/abs/2602.10884) |
| ⭐ **DriveWorld-VLA: Unifying World Modeling and Planning in Latent Space** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.06521-b31b1b.svg)](https://arxiv.org/abs/2602.06521) |
| **RaWMPC: Risk-aware World Model Predictive Control** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.23259-b31b1b.svg)](https://arxiv.org/abs/2602.23259) |
| **DiffusionHarmonizer: Online Generative Enhancement for Driving Simulation** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.24096-b31b1b.svg)](https://arxiv.org/abs/2602.24096) |
| ⭐ **A Survey of World Models for Autonomous Driving** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.11260-b31b1b.svg)](https://arxiv.org/abs/2501.11260) |
| ⭐ **Cosmos-Drive-Dreams** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.09042-b31b1b.svg)](https://arxiv.org/abs/2506.09042) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/nv-tlabs/Cosmos-Drive-Dreams) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://research.nvidia.com/labs/toronto-ai/cosmos_drive_dreams) |
| **Drive-OccWorld** | `AAAI 2025` | [![arXiv](https://img.shields.io/badge/arXiv-2408.14197-b31b1b.svg)](https://arxiv.org/abs/2408.14197) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/yuyang-cloud/Drive-OccWorld) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://drive-occworld.github.io/) |
| **DriveDreamer-2** | `AAAI 2025` | [![arXiv](https://img.shields.io/badge/arXiv-2403.06845-b31b1b.svg)](https://arxiv.org/abs/2403.06845) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://drivedreamer2.github.io/) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://drivedreamer2.github.io/) |
| **DriveDreamer4D** | `CVPR 2025` | [![arXiv](https://img.shields.io/badge/arXiv-2410.13571-b31b1b.svg)](https://arxiv.org/abs/2410.13571) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/GigaAI-research/DriveDreamer4D) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://drivedreamer4d.github.io/) |
| **MagicDrive-V2** | `ICCV 2025` | [![arXiv](https://img.shields.io/badge/arXiv-2411.13807-b31b1b.svg)](https://arxiv.org/abs/2411.13807) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://gaoruiyuan.com/magicdrive-v2/) |
| **SubjectDrive** | `AAAI 2025` | [![arXiv](https://img.shields.io/badge/arXiv-2403.19438-b31b1b.svg)](https://arxiv.org/abs/2403.19438) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://subjectdrive.github.io/) |
| **DriveDreamer** | `ECCV 2024` | [![arXiv](https://img.shields.io/badge/arXiv-2309.09777-b31b1b.svg)](https://arxiv.org/abs/2309.09777) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/JeffWang987/DriveDreamer) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://drivedreamer.github.io/) |
| **DriveWorld** | `CVPR 2024` | [![arXiv](https://img.shields.io/badge/arXiv-2405.04390-b31b1b.svg)](https://arxiv.org/abs/2405.04390) |
| **DrivingDiffusion** | `ECCV 2024` | [![arXiv](https://img.shields.io/badge/arXiv-2310.07771-b31b1b.svg)](https://arxiv.org/abs/2310.07771) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/shalfun/DrivingDiffusion) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://drivingdiffusion.github.io/) |
| **DrivingDojo Dataset** | `IPS 2024` | [![arXiv](https://img.shields.io/badge/arXiv-2410.10738-b31b1b.svg)](https://arxiv.org/abs/2410.10738) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://drivingdojo.github.io/) |
| **MagicDrive** | `ICLR 2024` | [![arXiv](https://img.shields.io/badge/arXiv-2310.02601-b31b1b.svg)](https://arxiv.org/abs/2310.02601) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/cure-lab/MagicDrive) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://gaoruiyuan.com/magicdrive/) |
| **Workshop on Foundation Models for Autonomous Systems** | `CVPR 2024` | - |
| **AdaptiveDriver** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2406.10714-b31b1b.svg)](https://arxiv.org/abs/2406.10714) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://arunbalajeev.github.io/world_models_planning/world_model_paper.html) |
| **Dream to Drive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2502.10012-b31b1b.svg)](https://arxiv.org/abs/2502.10012) |
| **Dream4Drive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.19195-b31b1b.svg)](https://arxiv.org/abs/2510.19195) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wm-research.github.io/Dream4Drive/) |
| **Drive-JEPA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2601.22032-b31b1b.svg)](https://arxiv.org/abs/2601.22032) |
| **DriveGenVLM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2408.16647-b31b1b.svg)](https://arxiv.org/abs/2408.16647) |
| **DrivePhysica** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.08410-b31b1b.svg)](https://arxiv.org/abs/2412.08410) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://metadrivescape.github.io/papers_project/DrivePhysica/page.html) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://metadrivescape.github.io/papers_project/DrivePhysica/page.html) |
| **DriveVLA-W0** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.12796-b31b1b.svg)](https://arxiv.org/abs/2510.12796) |
| **DrivingGPT** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.18607-b31b1b.svg)](https://arxiv.org/abs/2412.18607) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://rogerchern.github.io/DrivingGPT/) |
| ⭐ **GAIA-2** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.20523-b31b1b.svg)](https://arxiv.org/abs/2503.20523) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wayve.ai/thinking/scaling-gaia-2/) |
| ⭐ **WorldLens** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.10958-b31b1b.svg)](https://arxiv.org/abs/2512.10958) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://worldlens-ad.github.io) |
| **STAGE** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.13138-b31b1b.svg)](https://arxiv.org/abs/2506.13138) |
| **ReSim** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.09981-b31b1b.svg)](https://arxiv.org/abs/2506.09981) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/OpenDriveLab/ReSim) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://opendrivelab.com/ReSim) |
| **Dreamland** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.08006-b31b1b.svg)](https://arxiv.org/abs/2506.08006) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://metadriverse.github.io/dreamland/) |
| **LongDWM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.01546-b31b1b.svg)](https://arxiv.org/abs/2506.01546) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wang-xiaodong1899.github.io/longdwm/) |
| **GeoDrive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.22421-b31b1b.svg)](https://arxiv.org/abs/2505.22421) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/antonioo-c/GeoDrive) |
| **FutureSightDrive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.17685-b31b1b.svg)](https://arxiv.org/abs/2505.17685) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/MIV-XJTU/FSDrive) |
| **Raw2Drive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.16394-b31b1b.svg)](https://arxiv.org/abs/2505.16394) |
| **VL-SAFE** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.16377-b31b1b.svg)](https://arxiv.org/abs/2505.16377) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://ys-qu.github.io/vlsafe-website/) |
| **PosePilot** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.01729-b31b1b.svg)](https://arxiv.org/abs/2505.01729) |
| **DriVerse** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.18576-b31b1b.svg)](https://arxiv.org/abs/2504.18576) |
| **MiLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.15875-b31b1b.svg)](https://arxiv.org/abs/2503.15875) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/xiaomi-mlab/mila.github.io) |
| **SimWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.13952-b31b1b.svg)](https://arxiv.org/abs/2503.13952) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/Li-Zn-H/SimWorld) |
| **UniFuture** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.13587-b31b1b.svg)](https://arxiv.org/abs/2503.13587) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/dk-liang/UniFuture) |
| **EOT-WM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.09215-b31b1b.svg)](https://arxiv.org/abs/2503.09215) |
| **MaskGWM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2502.11663-b31b1b.svg)](https://arxiv.org/abs/2502.11663) |
| **HERMES** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.14729-b31b1b.svg)](https://arxiv.org/abs/2501.14729) |
| **AdaWM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.13072-b31b1b.svg)](https://arxiv.org/abs/2501.13072) |
| **AD-L-JEPA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.04969-b31b1b.svg)](https://arxiv.org/abs/2501.04969) |
| **DrivingWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.19505-b31b1b.svg)](https://arxiv.org/abs/2412.19505) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/YvanYin/DrivingWorld) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://huxiaotaostasy.github.io/DrivingWorld/index.html) |
| **GEM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.11198-b31b1b.svg)](https://arxiv.org/abs/2412.11198) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://vita-epfl.github.io/GEM.github.io/) |
| **GaussianWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.04380-b31b1b.svg)](https://arxiv.org/abs/2412.04380) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/zuosc19/GaussianWorld) |
| **Doe-1** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.09627-b31b1b.svg)](https://arxiv.org/abs/2412.09627) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wzzheng.net/Doe/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/wzzheng/Doe) |
| **InfiniCube** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.03934-b31b1b.svg)](https://arxiv.org/abs/2412.03934) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://research.nvidia.com/labs/toronto-ai/infinicube/) |
| **InfinityDrive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.01522-b31b1b.svg)](https://arxiv.org/abs/2412.01522) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://metadrivescape.github.io/papers_project/InfinityDrive/page.html) |
| **ReconDreamer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2411.19548-b31b1b.svg)](https://arxiv.org/abs/2411.19548) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://recondreamer.github.io/) |
| **Imagine-2-Drive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2411.10171-b31b1b.svg)](https://arxiv.org/abs/2411.10171) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://anantagrg.github.io/Imagine-2-Drive.github.io/) |
| **DynamicCity** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.18084-b31b1b.svg)](https://arxiv.org/abs/2410.18084) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://dynamic-city.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/3DTopia/DynamicCity) |
| **DOME** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.10429-b31b1b.svg)](https://arxiv.org/abs/2410.10429) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://gusongen.github.io/DOME) |
| **SSR** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2409.18341-b31b1b.svg)](https://arxiv.org/abs/2409.18341) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/PeidongLi/SSR) |
| **LatentDriver** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2409.15730-b31b1b.svg)](https://arxiv.org/abs/2409.15730) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Sephirex-X/LatentDriver) |
| **RenderWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2409.11356-b31b1b.svg)](https://arxiv.org/abs/2409.11356) |
| **OccLLaMA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2409.03272-b31b1b.svg)](https://arxiv.org/abs/2409.03272) |
| **CarFormer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2407.15843-b31b1b.svg)](https://arxiv.org/abs/2407.15843) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://kuis-ai.github.io/CarFormer/) |
| **BEVWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2407.05679-b31b1b.svg)](https://arxiv.org/abs/2407.05679) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/zympsyche/BevWorld) |
| **TOKEN** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2407.00959-b31b1b.svg)](https://arxiv.org/abs/2407.00959) |
| **SimGen** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2406.09386-b31b1b.svg)](https://arxiv.org/abs/2406.09386) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://metadriverse.github.io/simgen/) |
| **UnO** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2406.08691-b31b1b.svg)](https://arxiv.org/abs/2406.08691) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://waabi.ai/research/uno) |
| **LAW** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2406.08481-b31b1b.svg)](https://arxiv.org/abs/2406.08481) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/BraveGroup/LAW) |
| **Delphi** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2406.01349-b31b1b.svg)](https://arxiv.org/abs/2406.01349) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/westlake-autolab/Delphi) |
| **OccSora** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.20337-b31b1b.svg)](https://arxiv.org/abs/2405.20337) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/wzzheng/OccSora) |
| **MagicDrive3D** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.14475-b31b1b.svg)](https://arxiv.org/abs/2405.14475) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://gaoruiyuan.com/magicdrive3d/) |
| **Vista** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.17398-b31b1b.svg)](https://arxiv.org/abs/2405.17398) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/OpenDriveLab/Vista) |
| **CarDreamer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.09111-b31b1b.svg)](https://arxiv.org/abs/2405.09111) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/ucd-dare/CarDreamer) |
| **DriveSim** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.05956-b31b1b.svg)](https://arxiv.org/abs/2405.05956) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/sreeramsa/DriveSim) |
| **LidarDM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2404.02903-b31b1b.svg)](https://arxiv.org/abs/2404.02903) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/vzyrianov/lidardm) |
| **GenAD** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2403.09630-b31b1b.svg)](https://arxiv.org/abs/2403.09630) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/OpenDriveLab/DriveAGI?tab=readme-ov-file#genad-dataset-opendv-youtube) |
| **GenAD (End-to-End)** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2402.11502-b31b1b.svg)](https://arxiv.org/abs/2402.11502) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/wzzheng/GenAD) |
| **ViDAR** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2312.17655-b31b1b.svg)](https://arxiv.org/abs/2312.17655) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/OpenDriveLab/ViDAR) |
| **Drive-WM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2311.17918-b31b1b.svg)](https://arxiv.org/abs/2311.17918) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/BraveGroup/Drive-WM) |
| **Cam4DOCC** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2311.17663-b31b1b.svg)](https://arxiv.org/abs/2311.17663) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/haomo-ai/Cam4DOcc) |
| **Panacea** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2311.16813-b31b1b.svg)](https://arxiv.org/abs/2311.16813) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://panacea-ad.github.io/) |
| **OccWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2311.16038-b31b1b.svg)](https://arxiv.org/abs/2311.16038) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/wzzheng/OccWorld) |
| **SafeDreamer** | `-` | [![OpenReview](https://img.shields.io/badge/OpenReview-Paper-8E44AD.svg)](https://openreview.net/forum?id=tsE5HLYtYg) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/PKU-Alignment/SafeDreamer) |
| **SEM2** | `-` | [![Paper](https://img.shields.io/badge/Paper-Link-blue)](https://ieeexplore.ieee.org/abstract/document/10538211/) |
| **DrivingGen** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2601.01528-b31b1b.svg)](https://arxiv.org/abs/2601.01528) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://drivinggen-bench.github.io/) |
| **DrivingWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.19505-b31b1b.svg)](https://arxiv.org/abs/2412.19505) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/YvanYin/DrivingWorld) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://huxiaotaostasy.github.io/DrivingWorld/index.html) |
| **GenieDrive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.12751-b31b1b.svg)](https://arxiv.org/abs/2512.12751) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://huster-yzy.github.io/geniedrive_project_page/) |
| **ImagiDrive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.11428-b31b1b.svg)](https://arxiv.org/abs/2508.11428) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/fudan-zvg/ImagiDrive) |
| **Imagine-2-Drive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2411.10171-b31b1b.svg)](https://arxiv.org/abs/2411.10171) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://anantagrg.github.io/Imagine-2-Drive.github.io/) |
| **InfinityDrive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.01522-b31b1b.svg)](https://arxiv.org/abs/2412.01522) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://metadrivescape.github.io/papers_project/InfinityDrive/page.html) |
| **Interplay Between Video Generation and World Models in Autonomous Driving** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2411.02914-b31b1b.svg)](https://arxiv.org/abs/2411.02914) |
| **LatentDriver** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2409.15730-b31b1b.svg)](https://arxiv.org/abs/2409.15730) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Sephirex-X/LatentDriver) |
| **MagicDrive3D** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.14475-b31b1b.svg)](https://arxiv.org/abs/2405.14475) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://gaoruiyuan.com/magicdrive3d/) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://gaoruiyuan.com/magicdrive3d/) |
| **MoVieDrive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.14327-b31b1b.svg)](https://arxiv.org/abs/2508.14327) |
| **Think Before You Drive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.03454-b31b1b.svg)](https://arxiv.org/abs/2512.03454) |
| **Think2Drive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2402.16720-b31b1b.svg)](https://arxiv.org/abs/2402.16720) |
| **TrafficBots** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2303.04116-b31b1b.svg)](https://arxiv.org/abs/2303.04116) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/zhejz/TrafficBots) |
| **UniDrive-WM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2601.04453-b31b1b.svg)](https://arxiv.org/abs/2601.04453) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://unidrive-wm.github.io/UniDrive-WM) |
| **World Models for Autonomous Driving: An Initial Survey** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2403.02622-b31b1b.svg)](https://arxiv.org/abs/2403.02622) |
| **World4Drive** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2507.00603-b31b1b.svg)](https://arxiv.org/abs/2507.00603) |
| **`CVPR 24 Workshop & Challenge | OpenDriveLab`** | `-` | - |
| **`CVPR 25 Workshop & Challenge | OpenDriveLab`** | `-` | - |

---

### Papers by Application

#### 🚗 Autonomous Driving

World models for scene prediction, planning, and simulation in self-driving vehicles.

> 📄 See complete list above (40 papers total)

---

#### 🤖 Embodied AI & Robotics

World models for manipulation, navigation, and interaction in physical environments.


| ⭐ **DreamDojo** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.06949-b31b1b.svg)](https://arxiv.org/abs/2602.06949) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://huggingface.co/nvidia/DreamDojo) |
| ⭐ **World Models as Data Engine** | `arXiv 2025` | [![arXiv](https://img.shields.io/badge/arXiv-2511.19861-b31b1b.svg)](https://arxiv.org/abs/2511.19861) |
#### 🤖 Embodied AI Papers

| Paper | Venue | Resources |
|-------|-------|-----------|
| **GaussTwin: Unified Simulation and Correction with Gaussian Splatting for Robotic Digital Twins** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2603.05108-b31b1b.svg)](https://arxiv.org/abs/2603.05108) |
| ⭐ **"Learning Primitive Embodied World Models: Towards Scalable Robotic Learning"** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.20840-b31b1b.svg)](https://arxiv.org/pdf/2508.20840) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://qiaosun22.github.io/PrimitiveWorld/) |
| ⭐ **Agent Learning via Early Experience** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.08558-b31b1b.svg)](https://arxiv.org/pdf/2510.08558) |
| ⭐ **General agents Contain World Models** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.01622-b31b1b.svg)](https://arxiv.org/abs/2506.01622) |
| ⭐ **Persistent Embodied World Models** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.05495-b31b1b.svg)](https://arxiv.org/abs/2505.05495) |
| ⭐ **Self-Improving Embodied Foundation Models** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.15155-b31b1b.svg)](https://arxiv.org/abs/2509.15155) |
| ⭐ **World Models for Embodied AI** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.16732-b31b1b.svg)](https://arxiv.org/abs/2510.16732) |
| **Workshop on Embodied World Models for Decision Making** | `IPS 2025` | - |
| **EmbodieDreamer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2507.05198-b31b1b.svg)](https://arxiv.org/pdf/2507.05198) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/GigaAI-research/EmbodieDreamer) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://embodiedreamer.github.io/) |
| **Embodied AI Agents: Modeling the World** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.22355-b31b1b.svg)](https://arxiv.org/abs/2506.22355) |
| **PhysicalAgent** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.13903-b31b1b.svg)](https://arxiv.org/abs/2509.13903) |
| **Video Agent** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.10076-b31b1b.svg)](http://arxiv.org/abs/2410.10076) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://video-as-agent.github.io/) |
| **Web Agents with World Models** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.13232-b31b1b.svg)](https://arxiv.org/abs/2410.13232) |

| **View-Consistent 4D World Model** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.09878-b31b1b.svg)](https://arxiv.org/abs/2602.09878) |
| ⭐ **World Models as Reliable Simulators** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.13977-b31b1b.svg)](https://arxiv.org/abs/2602.13977) |
#### 🦾 Robotics Papers

| Paper | Venue | Resources |
|-------|-------|-----------|
| ⭐ **"Learning Primitive Embodied World Models: Towards Scalable Robotic Learning"** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.20840-b31b1b.svg)](https://arxiv.org/pdf/2508.20840) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://qiaosun22.github.io/PrimitiveWorld/) |
| ⭐ **"Multi-Task Interactive Robot Fleet Learning with Visual World Models"** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.22689-b31b1b.svg)](https://arxiv.org/abs/2410.22689) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/UT-Austin-RPL/sirius-fleet/) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://ut-austin-rpl.github.io/sirius-fleet/) |
| ⭐ **"Object-Centric World Model for Language-Guided Manipulation" [![arXiv](https://img** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.06170-b31b1b.svg)](https://arxiv.org/abs/2503.06170) |
| ⭐ **Robotic World Model** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.10100-b31b1b.svg)](https://arxiv.org/abs/2501.10100) |
| ⭐ **Genie Envisioner** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.05635-b31b1b.svg)](https://arxiv.org/abs/2508.05635) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://genie-envisioner.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/AgibotTech/Genie-Envisioner) |
| ⭐ **WoW** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.22642-b31b1b.svg)](https://arxiv.org/abs/2509.22642) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wow-world-model.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/wow-world-model/wow-world-model) |
| **UnifoLM-WMA-0** | `-` | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://unigen-x.github.io/unifolm-world-model-action.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/unitreerobotics/unifolm-world-model-action/tree/main) |
| ⭐ **iVideoGPT** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.15223-b31b1b.svg)](https://arxiv.org/abs/2405.15223) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://thuml.github.io/iVideoGPT/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/thuml/iVideoGPT) |
| ⭐ **PointWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2601.03782-b31b1b.svg)](https://www.arxiv.org/abs/2601.03782) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://point-world.github.io) |
| ⭐ **Dex-WM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.13644-b31b1b.svg)](https://arxiv.org/abs/2512.13644) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://raktimgg.github.io/dexwm/) |
| ⭐ **FLARE** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.15659-b31b1b.svg)](http://arxiv.org/abs/2505.15659) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://research.nvidia.com/labs/gear/flare/) |
| ⭐ **Enerverse** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.01895-b31b1b.svg)](http://arxiv.org/abs/2501.01895) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://sites.google.com/view/enerverse) |
| ⭐ **AgiBot-World** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.06669-b31b1b.svg)](https://arxiv.org/abs/2503.06669) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://agibot-world.com/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/OpenDriveLab/AgiBot-World) |
| ⭐ **DyWA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.16806-b31b1b.svg)](https://arxiv.org/abs/2503.16806) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://pku-epic.github.io/DyWA/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/jiangranlv/DyWA) |
| ⭐ **TesserAct** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.20995-b31b1b.svg)](https://arxiv.org/abs/2504.20995) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://tesseractworld.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/UMass-Embodied-AGI/TesserAct) |
| ⭐ **DreamGen** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.12705-b31b1b.svg)](https://arxiv.org/abs/2505.12705) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://research.nvidia.com/labs/gear/dreamgen/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/nvidia/GR00T-dreams) |
| ⭐ **HiP** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2309.08587-b31b1b.svg)](http://arxiv.org/abs/2309.08587) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://hierarchical-planning-foundation-model.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/anuragajay/hip/tree/main) |
| **PAR** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.09822-b31b1b.svg)](https://arxiv.org/abs/2508.09822) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://hcplab-sysu.github.io/PhysicalAutoregressiveModel/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/HCPLab-SYSU/PhysicalAutoregressiveModel) |
| **iMoWM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.07313-b31b1b.svg)](https://arxiv.org/abs/2510.07313) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://xingyoujun.github.io/imowm/) |
| **WristWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.07313-b31b1b.svg)](https://arxiv.org/abs/2510.07313) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wrist-world.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/XuWuLingYu/WristWorld) |
| **EMMA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.22407-b31b1b.svg)](https://arxiv.org/abs/2509.22407) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://emma-gigaai.github.io) |
| **PhysTwin** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.17973-b31b1b.svg)](http://arxiv.org/abs/2503.17973) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://jianghanxiao.github.io/phystwin-web/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Jianghanxiao/PhysTwin) |
| ⭐ **KeyWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.21027-b31b1b.svg)](https://arxiv.org/abs/2509.21027) |
| **World4RL** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.19080-b31b1b.svg)](https://arxiv.org/abs/2509.19080) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://world4rl.github.io) |
| ⭐ **SAMPO** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.15536-b31b1b.svg)](https://arxiv.org/abs/2509.15536) |
| ⭐ **GWM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.17600-b31b1b.svg)](https://arxiv.org/abs/2508.17600) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://gaussian-world-model.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Gaussian-World-Model/gaussianwm) |
| ⭐ **Flow-as-Action** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2507.13340-b31b1b.svg)](https://arxiv.org/abs/2507.13340) |
| **RoboScape** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.23135-b31b1b.svg)](https://arxiv.org/abs/2506.23135) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/tsinghua-fib-lab/RoboScape) |
| ⭐ **ParticleFormer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.23126-b31b1b.svg)](https://arxiv.org/abs/2506.23126) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://suninghuang19.github.io/particleformer_page/) |
| **ManiGaussian++** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.19842-b31b1b.svg)](https://arxiv.org/abs/2506.19842) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/April-Yz/ManiGaussian_Bimanual) |
| **GAF** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.14135-b31b1b.svg)](https://arxiv.org/abs/2506.14135) [![Website](https://img.shields.io/badge/Website-Link-blue)](http://chaiying1.github.io/GAF.github.io/project_page/) |
| ⭐ **3DFlowAction** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.06199-b31b1b.svg)](https://arxiv.org/abs/2506.06199) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Hoyyyaard/3DFlowAction/) |
| ⭐ **ORV** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.03079-b31b1b.svg)](https://arxiv.org/abs/2506.03079) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/OrangeSodahub/ORV) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://orangesodahub.github.io/ORV/) |
| ⭐ **WoMAP** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.01600-b31b1b.svg)](https://arxiv.org/abs/2506.01600) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robot-womap.github.io) |
| ⭐ **OSVI-WM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.20425-b31b1b.svg)](https://arxiv.org/abs/2505.20425) |
| ⭐ **LaDi-WM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.11528-b31b1b.svg)](https://arxiv.org/abs/2505.11528) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://guhuangai.github.io/LaDiWM.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/GuHuangAI/LaDiWM) |
| **FlowDreamer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.10075-b31b1b.svg)](https://arxiv.org/abs/2505.10075) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://sharinka0715.github.io/FlowDreamer/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/sharinka0715/FlowDreamer/) |
| **PIN-WM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.16693-b31b1b.svg)](https://arxiv.org/abs/2504.16693) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://pinwm.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/XuAdventurer/PIN-WM) |
| **RoboMaster** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.01943-b31b1b.svg)](http://arxiv.org/abs/2506.01943) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://fuxiao0719.github.io/projects/robomaster/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/KwaiVGI/RoboMaster) |
| **ManipDreamer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.16464-b31b1b.svg)](https://arxiv.org/abs/2504.16464) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://myendless1.github.io/ManipDreamer/) |
| ⭐ **AdaWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.18938-b31b1b.svg)](https://arxiv.org/abs/2503.18938) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://adaptable-world-model.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Little-Podi/AdaWorld) |
| ⭐ **EVA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.15461-b31b1b.svg)](https://arxiv.org/abs/2410.15461) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://sites.google.com/view/eva-publi) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/litwellchi/EmbodiedVideoAnticipator?tab=readme-ov-file) |
| **DexSim2Real²** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2409.08750-b31b1b.svg)](https://arxiv.org/abs/2409.08750) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/jiangtaoran/DexSim2Real2?tab=readme-ov-file) |
| ⭐ **LUMOS** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.10370-b31b1b.svg)](https://arxiv.org/abs/2503.10370) [![Website](https://img.shields.io/badge/Website-Link-blue)](http://lumos.cs.uni-freiburg.de/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/nematoli/lumos) |
| ⭐ **DEMO³** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.01837-b31b1b.svg)](https://arxiv.org/abs/2503.01837) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://adrialopezescoriza.github.io/demo3/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/adrialopezescoriza/demo3) |
| **RoboHorizon** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.06605-b31b1b.svg)](https://arxiv.org/abs/2501.06605) |
| **Dream to Manipulate** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.14957-b31b1b.svg)](https://arxiv.org/abs/2412.14957) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://leobarcellona.github.io/DreamToManipulate/) |
| ⭐ **RoboDreamer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2404.12377-b31b1b.svg)](https://arxiv.org/abs/2404.12377) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/rainbow979/robodreamer) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robovideo.github.io) |
| ⭐ **Vidar** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2404.12377-b31b1b.svg)](https://arxiv.org/abs/2507.12898) |
| **ManiGaussian** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2403.08321-b31b1b.svg)](https://arxiv.org/abs/2403.08321) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/GuanxingLu/ManiGaussian) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://guanxinglu.github.io/ManiGaussian/) |
| ⭐ **WHALE** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2411.05619-b31b1b.svg)](https://arxiv.org/abs/2411.05619) |
| ⭐ **VisualPredicator** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.23156-b31b1b.svg)](https://arxiv.org/abs/2410.23156) |
| **PIVOT-R** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.10394-b31b1b.svg)](https://arxiv.org/pdf/2410.10394) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://abliao.github.io/PIVOT-R/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/abliao/PIVOT-R) |
| **Video2Action** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2411.07223-b31b1b.svg)](http://arxiv.org/abs/2411.07223) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://video-to-action.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/video-to-action/video-to-action-release) |
| **Diffuser** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2205.09991-b31b1b.svg)](http://arxiv.org/abs/2205.09991) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://diffusion-planning.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/jannerm/diffuser) |
| **Decision Diffuser** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2211.15657-b31b1b.svg)](http://arxiv.org/abs/2211.15657) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/zbzhu99/decision-diffuser-jax) |

#### 🚶 Navigation Papers

| Paper | Venue | Resources |
|-------|-------|-----------|
| ⭐ **NWM (Navigation World Models)** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.03572-b31b1b.svg)](https://arxiv.org/abs/2412.03572) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.amirbar.net/nwm/) |
| ⭐ **MindJourney** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2507.12508-b31b1b.svg)](https://arxiv.org/abs/2507.12508) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://umass-embodied-agi.github.io/MindJourney) |
| **NavMorph** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.23468-b31b1b.svg)](https://arxiv.org/abs/2506.23468) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Feliciaxyao/NavMorph) |
| **Unified World Models** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.08713-b31b1b.svg)](https://arxiv.org/abs/2510.08713) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/F1y1113/UniWM) |
| **RECON** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2104.05859-b31b1b.svg)](http://arxiv.org/abs/2104.05859) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://sites.google.com/view/recon-robot) |
| **WMNav** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.02247-b31b1b.svg)](https://arxiv.org/abs/2503.02247) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://b0b8k1ng.github.io/WMNav/) |
| **NaVi-WM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.23509-b31b1b.svg)](https://arxiv.org/abs/2510.23509) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://sites.google.com/view/NaviWM) |
| **AIF** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.23258-b31b1b.svg)](https://arxiv.org/abs/2510.23258) |
| **X-MOBILITY** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2410.17491-b31b1b.svg)](https://arxiv.org/abs/2410.17491) |
| **MWM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2206.14244-b31b1b.svg)](http://arxiv.org/abs/2206.14244) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://sites.google.com/view/mwm-rl) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/younggyoseo/MWM) |

#### 🦿 Locomotion Papers

| Paper | Venue | Resources |
|-------|-------|-----------|
| ⭐ **Ego-VCP** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.11682-b31b1b.svg)](https://arxiv.org/abs/2510.11682) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://ego-vcp.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/HybridRobotics/Ego-VCP) |
| ⭐ **RWM-O** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.16680-b31b1b.svg)](https://arxiv.org/abs/2504.16680) |
| ⭐ **DWL** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2408.14472-b31b1b.svg)](https://arxiv.org/abs/2408.14472) |
| **HRSSM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.06263-b31b1b.svg)](https://arxiv.org/abs/2405.06263) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/bit1029public/HRSSM) |
| **WMP** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2409.16784-b31b1b.svg)](https://arxiv.org/abs/2409.16784) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wmp-loco.github.io/) |
| **TrajWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2502.01366-b31b1b.svg)](https://arxiv.org/abs/2502.01366) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/thuml/TrajWorld) |
| **Puppeteer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.18418-b31b1b.svg)](https://arxiv.org/abs/2405.18418) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://nicklashansen.com/rlpuppeteer) |
| **ProTerrain** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.19364-b31b1b.svg)](https://arxiv.org/abs/2510.19364) |
| **Occupancy World Model** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2505.05512-b31b1b.svg)](https://arxiv.org/abs/2505.05512) |
| ⭐ **1X World Model** | `-` | [![Blog](https://img.shields.io/badge/Blog-Link-orange)](https://www.1x.tech/discover/1x-world-model) |
| ⭐ **GROOT-Dreams** | `-` | [![Blog](https://img.shields.io/badge/Blog-Link-orange)](https://blogs.nvidia.com/blog/nvidia-gtc-washington-dc-2025-news/#gr00t-dreams) |
| **Humanoid World Models** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.01182-b31b1b.svg)](https://arxiv.org/abs/2506.01182) |
| **Ego-Agent** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2502.05857-b31b1b.svg)](https://arxiv.org/abs/2502.05857) |
| **D²PO** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.10480-b31b1b.svg)](https://arxiv.org/abs/2503.10480) |
| **COMBO** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2404.10775-b31b1b.svg)](https://arxiv.org/abs/2404.10775) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://vis-www.cs.umass.edu/combo/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/UMass-Foundation-Model/COMBO) |

#### 🤖💬 Vision-Language-Action (VLA) Models

World models integrated with vision-language-action architectures for robotic control.

| Paper | Venue | Resources |
|-------|-------|-----------|
| ⭐ **CoT-VLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.22020-b31b1b.svg)](https://arxiv.org/abs/2503.22020) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://cot-vla.github.io/) |
| ⭐ **UP-VLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.18867-b31b1b.svg)](https://arxiv.org/abs/2501.18867) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/CladernyJorn/UP-VLA) |
| ⭐ **VPP** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.14803-b31b1b.svg)](https://arxiv.org/abs/2412.14803) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://video-prediction-policy.github.io) |
| ⭐ **MinD** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.18897-b31b1b.svg)](https://arxiv.org/abs/2506.18897) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://manipulate-in-dream.github.io/) |
| ⭐ **DreamVLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2507.04447-b31b1b.svg)](https://arxiv.org/abs/2507.04447) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Zhangwenyao1/DreamVLA) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://zhangwenyao1.github.io/DreamVLA/) |
| ⭐ **WorldVLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.21539-b31b1b.svg)](https://arxiv.org/abs/2506.21539) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/alibaba-damo-academy/WorldVLA) |
| **3D-VLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2403.09631-b31b1b.svg)](https://arxiv.org/abs/2403.09631) |
| **LAWM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.18428-b31b1b.svg)](https://arxiv.org/abs/2509.18428) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/baheytharwat/lawm) |
| ⭐ **UniVLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.19850-b31b1b.svg)](https://arxiv.org/abs/2506.19850) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://robertwyq.github.io/univla.github.) |
| ⭐ **dVLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.25681-b31b1b.svg)](https://arxiv.org/abs/2509.25681) |
| ⭐ **UD-VLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2511.01718-b31b1b.svg)](https://arxiv.org/abs/2511.01718) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/OpenHelix-Team/UD-VLA) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://irpn-eai.github.io/UD-VLA.github.io/) |
| **Goal-VLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.23919-b31b1b.svg)](https://arxiv.org/abs/2506.23919) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://nus-lins-lab.github.io/goalvlaweb/) |
| **Vidarc** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.17661-b31b1b.svg)](https://arxiv.org/abs/2512.17661) |
| ⭐ **VideoVLA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.06963-b31b1b.svg)](https://arxiv.org/abs/2512.06963) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://videovla-nips2025.github.io) |
| ⭐ **Motus** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.13030-b31b1b.svg)](https://arxiv.org/abs/2512.13030) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://motus-robotics.github.io/motus) |
| ⭐ **mimic-video** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.15692-b31b1b.svg)](https://arxiv.org/abs/2512.15692) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://mimic-video.github.io) |
| ⭐ **Ctrl-World** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.10125-b31b1b.svg)](https://arxiv.org/pdf/2510.10125) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://ctrl-world.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Robert-gyj/Ctrl-World) |
| **VLA-RFT** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.00406-b31b1b.svg)](https://arxiv.org/abs/2510.00406) |
| **World-Env** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.24948-b31b1b.svg)](https://arxiv.org/abs/2509.24948) |
| ⭐ **GigaBrain-0.5M** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2602.12099-b31b1b.svg)](https://arxiv.org/abs/2602.12099v1) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://gigabrain05m.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/open-gigaai/giga-brain-0) |
| **RISE** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2602.11075-b31b1b.svg)](https://arxiv.org/abs/2602.11075) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://opendrivelab.com/kai0-rl/) |
| **GigaBrain-0** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.19430-b31b1b.svg)](https://arxiv.org/abs/2510.19430) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://gigabrain0.github.io/) |
| **WMPO** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2511.09515-b31b1b.svg)](https://arxiv.org/abs/2511.09515) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wm-po.github.io) |

#### 🎯 Policy Learning with World Models

General policy learning methods leveraging world models for embodied AI.

| Paper | Venue | Resources |
|-------|-------|-----------|
| ⭐ **LingBot-VA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2601.21998-b31b1b.svg)](https://arxiv.org/abs/2601.21998v1) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://technology.robbyant.com/lingbot-va) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/Robbyant/lingbot-va) |
| ⭐ **UWM** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.02792-b31b1b.svg)](https://arxiv.org/abs/2504.02792) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://weirdlabuw.github.io/uwm/) |
| ⭐ **UVA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.00200-b31b1b.svg)](https://arxiv.org/abs/2503.00200) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://unified-video-action-model.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/ShuangLI59/unified_video_action) |
| **DiWA** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.03645-b31b1b.svg)](https://arxiv.org/abs/2508.03645) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://diwa.cs.uni-freiburg.de) |
| ⭐ **Dreamerv4** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.24527-b31b1b.svg)](https://arxiv.org/abs/2509.24527) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://danijar.com/project/dreamer4/) |
| **LVP** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2512.15840-b31b1b.svg)](https://arxiv.org/abs/2512.15840) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.boyuan.space/large-video-planner/) |
| ⭐ **LDA-1B** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2602.12215-b31b1b.svg)](https://arxiv.org/abs/2602.12215) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://pku-epic.github.io/LDA/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/jiangranlv/latent-dynamics-action) |

---

#### 🎮 Game Simulation & XR

World models for procedural content generation and interactive experiences.


| ⭐ **Web World Models** | `arXiv 2025` | [![arXiv](https://img.shields.io/badge/arXiv-2512.23676-b31b1b.svg)](https://arxiv.org/abs/2512.23676) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://ai.princeton.edu/news/2026/web-world-model-creates-unlimited-website-environments-without-sacrificing-logical) |
| **Large-Scale World Model for Web Agent** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.14721-b31b1b.svg)](https://arxiv.org/abs/2602.14721) |
| **World-Model-Augmented Web Agents** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.15384-b31b1b.svg)](https://arxiv.org/abs/2602.15384) |
| **Multiplayer Video World Model in Minecraft** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.22208-b31b1b.svg)](https://arxiv.org/abs/2602.22208) |
#### 🎮 Game & Simulation Papers

| Paper | Venue | Resources |
|-------|-------|-----------|
| ⭐ **Is Sora a World Simulator** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.03520-b31b1b.svg)](https://arxiv.org/abs/2405.03520) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/GigaAI-research/General-World-Models-Survey) |
| ⭐ **Matrix-Game** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.18701-b31b1b.svg)](https://arxiv.org/abs/2506.18701) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/SkyworkAI/Matrix-Game) |
| ⭐ **Matrix-Game 2.0** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2508.13009-b31b1b.svg)](https://arxiv.org/abs/2508.13009) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/SkyworkAI/Matrix-Game/tree/main/Matrix-Game-2) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://matrix-game-v2.github.io/) |
| **AnimeGamer** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.01014-b31b1b.svg)](http://arxiv.org/abs/2504.01014) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://howe125.github.io/AnimeGamer.github.io/) |
| **GameFactory** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2501.08325-b31b1b.svg)](http://arxiv.org/abs/2501.08325) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/KwaiVGI/GameFactory) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://yujiwen.github.io/gamefactory/) |
| **Hunyuan-GameCraft-2** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2511.23429-b31b1b.svg)](https://arxiv.org/abs/2511.23429) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://hunyuan-gamecraft-2.github.io/) |
| **Interactive Generative Video as Next-Generation Game Engine** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.17359-b31b1b.svg)](http://arxiv.org/abs/2503.17359) |
| **Interplay Between Video Generation and World Models in Autonomous Driving** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2411.02914-b31b1b.svg)](https://arxiv.org/abs/2411.02914) |
| **World Models and Physical Simulation** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2507.00917-b31b1b.svg)](https://arxiv.org/abs/2507.00917) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/NJU3DV-LoongGroup/Embodied-World-Models-Survey) |
| ⭐ **GameNGen** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2408.14837-b31b1b.svg)](https://arxiv.org/abs/2408.14837) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://gamengen.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/google-research/google-research/tree/master/gamengen) |
| ⭐ **DIAMOND** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2405.12399-b31b1b.svg)](https://arxiv.org/abs/2405.12399) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://diamond-wm.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/eloialonso/diamond) |
| ⭐ **MineWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.07257-b31b1b.svg)](https://arxiv.org/abs/2504.07257) |
| ⭐ **HunyuanWorld 1.0** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2507.21809-b31b1b.svg)](https://arxiv.org/abs/2507.21809) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://hunyuanworld.github.io) |
| **Oasis** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2411.11763-b31b1b.svg)](https://arxiv.org/abs/2411.11763) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://oasis-model.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/etched-ai/open-oasis) |
| **Genie** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2402.15391-b31b1b.svg)](https://arxiv.org/abs/2402.15391) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://sites.google.com/view/genie-2024/home) |
| **Genie 2** | `-` | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/) |
| **WorldCrafter** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2412.09119-b31b1b.svg)](https://arxiv.org/abs/2412.09119) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://worldcrafter.github.io) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/sled-group/world-crafter) |
| **Cosmos** | `-` | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.nvidia.com/en-us/ai/cosmos/) |

---


#### 💡 Theory & Explainability

Theoretical foundations and explainability of world models.

| Paper | Venue | Resources |
|-------|-------|-----------|
| ⭐ **Inductive Biases in Transformers** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2602.06923-b31b1b.svg)](https://arxiv.org/abs/2602.06923) |
| ⭐ **Physical Grounding in World Models** | `arXiv 2026` | [![arXiv](https://img.shields.io/badge/arXiv-2601.15533-b31b1b.svg)](https://arxiv.org/abs/2601.15533) |

---

#### 👥 Social World Models & Multi-Agent Systems

World models for social interaction, multi-agent coordination, and human behavior prediction.

| Paper/Project | Type | Resources |
|---------------|------|-----------|
| **FreeAskWorld** | Framework | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/AIR-DISCOVER/FreeAskWorld) [![Paper](https://img.shields.io/badge/AAAI-2026-blue)]() |
| **Model-Based Social Navigation** | Navigation | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/ZJU-Robotics-Lab/model-based-social-navigation) |
| **SOMA: Socio-physical Model of Activities** | Activity Model | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/ease-crc/soma) |
| **Mini-Genie: Multi-Agent World Model** | Multi-Agent | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/danimelatru/Mini-Genie) |
| **Social World Model Simulation** | Simulation | [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/XuhuiZhou/social-world-model) |
| **MotionLM: Multi-Agent Motion Forecasting** | Prediction | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://waymo.com/research/motionlm/) |
| **Melting Pot: Multi-Agent RL Evaluation** | Benchmark | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://deepmind.google/blog/melting-pot-an-evaluation-suite-for-multi-agent-reinforcement-learning/) |

**Key Topics:**
- 🤝 Human-robot interaction modeling
- 🚶 Pedestrian behavior prediction
- 🎭 Social navigation in crowded environments
- 🤖 Multi-agent coordination and communication
- 🧠 Theory of mind for AI agents

> 📖 For more on multi-agent systems, see [Multi-Agent Reinforcement Learning](https://en.wikipedia.org/wiki/Multi-agent_reinforcement_learning)

---

#### 🔬 World Models for Science

World models applied to scientific domains including medicine, biology, and social sciences.

**Natural Science:**

| Paper | Venue | Resources |
|-------|-------|-----------|
| **World Models for Clinical Prediction** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2511.16333-b31b1b.svg)](https://arxiv.org/abs/2511.16333) |
| ⭐ **CellFlux** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2502.09775-b31b1b.svg)](https://arxiv.org/abs/2502.09775) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://yuhui-zh15.github.io/CellFlux/) |
| **CheXWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.13820-b31b1b.svg)](http://arxiv.org/abs/2504.13820) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/LeapLabTHU/CheXWorld) |
| **EchoWorld** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.13065-b31b1b.svg)](https://arxiv.org/abs/2504.13065) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/LeapLabTHU/EchoWorld) |
| **ODesign** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.22304-b31b1b.svg)](https://arxiv.org/pdf/2510.22304) [![Website](https://img.shields.io/badge/Website-Link-blue)](https://odesign.lglab.ac.cn) |
| ⭐ **SFP** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.04020-b31b1b.svg)](https://arxiv.org/abs/2510.04020) |
| **Xray2Xray** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.19055-b31b1b.svg)](https://arxiv.org/abs/2506.19055) |
| ⭐ **Medical World Model** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2506.02327-b31b1b.svg)](https://arxiv.org/abs/2506.02327) |
| **Surgical Vision World Model** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2503.02904-b31b1b.svg)](https://arxiv.org/abs/2503.02904) |

**Social Science:**

| Paper | Venue | Resources |
|-------|-------|-----------|
| **Social World Models** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2509.00559-b31b1b.svg)](https://arxiv.org/abs/2509.00559) |
| **Social World Model-Augmented Mechanism Design** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2510.19270-b31b1b.svg)](https://arxiv.org/abs/2510.19270) |
| **SocioVerse** | `-` | [![arXiv](https://img.shields.io/badge/arXiv-2504.10157-b31b1b.svg)](http://arxiv.org/abs/2504.10157) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/FudanDISC/SocioVerse) |

---

## 🎓 Learning Resources

### 📺 Talks & Presentations

Key talks and presentations on world models:

| Title | Speaker | Venue | Resources |
|-------|---------|-------|-----------|
| **A Path Towards Autonomous Machine Intelligence** | Yann LeCun | Meta AI | [![Video](https://img.shields.io/badge/Video-YouTube-red)](https://www.youtube.com/watch?v=OKkEdTchsiE) [![Paper](https://img.shields.io/badge/Paper-OpenReview-8E44AD.svg)](https://openreview.net/pdf?id=BZ5a1r-kVsf) |
| **World Models for Autonomous Driving** | Ashok Elluswamy | Tesla AI Day 2024 | [![Video](https://img.shields.io/badge/Video-YouTube-red)](https://www.youtube.com/watch?v=6x-Xb_uT7ts) |
| **GAIA-1: A Generative World Model for Autonomous Driving** | Wayve Team | NVIDIA GTC 2023 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://wayve.ai/thinking/gaia1/) |
| **NVIDIA Cosmos: Physical AI with World Foundation Models** | NVIDIA Team | GTC 2025 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.nvidia.com/en-us/ai/cosmos/) |
| **Genie: Generative Interactive Environments** | DeepMind Team | Tech Talk 2024 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://sites.google.com/view/genie-2024) |

> 📺 For complete list of talks (50+), see [docs/learning/talks.md](docs/learning/talks.md)

---

### 🎓 Courses & Tutorials

**Online Courses:**
- **Deep Reinforcement Learning** (UC Berkeley CS285) - Covers model-based RL and world models [![Website](https://img.shields.io/badge/Website-Link-blue)](http://rail.eecs.berkeley.edu/deeprlcourse/)
- **Stanford CS330: Deep Multi-Task and Meta Learning** - Includes world model architectures [![Website](https://img.shields.io/badge/Website-Link-blue)](https://cs330.stanford.edu/)
- **MIT 6.S898: Deep Learning** - Foundation models and world models [![Website](https://img.shields.io/badge/Website-Link-blue)](https://phillipi.github.io/6.s898/)

**Tutorials:**
- [Implementing DreamerV3 from Scratch](https://github.com/danijar/dreamerv3) - Official PyTorch implementation
- [World Models Tutorial](https://worldmodels.github.io/) - Interactive introduction to world models
- [CARLA Autonomous Driving Tutorial](https://carla.readthedocs.io/) - Simulation-based learning

> 🎓 For complete list of courses and tutorials (30+), see [docs/learning/tutorials.md](docs/learning/tutorials.md)

---

## 🔧 Practical Resources

### 📊 Datasets

**Autonomous Driving:**
- **nuScenes** - 1000 scenes with camera, LiDAR, radar [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.nuscenes.org/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/1903.11027)
- **Waymo Open Dataset** - 1000 segments, 200k frames [![Website](https://img.shields.io/badge/Website-Link-blue)](https://waymo.com/open/)
- **KITTI** - Classic autonomous driving benchmark [![Website](https://img.shields.io/badge/Website-Link-blue)](http://www.cvlibs.net/datasets/kitti/)
- **Argoverse 2** - 1000 scenarios, forecasting [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.argoverse.org/)
- **Occ3D** - 16k frames for occupancy prediction [![Website](https://img.shields.io/badge/Website-Link-blue)](https://tsinghua-mars-lab.github.io/Occ3D/)
- **CARLA** - Open-source driving simulator [![Website](https://img.shields.io/badge/Website-Link-blue)](https://carla.org/)

**Robotics:**
- **CALVIN** - 24k manipulation trajectories [![Website](https://img.shields.io/badge/Website-Link-blue)](http://calvin.cs.uni-freiburg.de/) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/mees/calvin)
- **RoboNet** - 15M robot manipulation frames [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.robonet.wiki/)
- **RoboCasa** - 100k kitchen manipulation trajectories [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robocasa.ai/)
- **Open X-Embodiment** - 1M+ multi-robot trajectories [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robotics-transformer-x.github.io/)
- **Habitat-Matterport 3D** - 90 indoor scenes [![Website](https://img.shields.io/badge/Website-Link-blue)](https://aihabitat.org/)

**Games:**
- **Minecraft** - Procedural 3D environments
- **Atari 2600** - Classic RL benchmark (57 games)
- **MineRL** - 60M frames of Minecraft gameplay [![Website](https://img.shields.io/badge/Website-Link-blue)](https://minerl.io/)

> 📊 For complete list of datasets (50+), see [docs/resources/datasets.md](docs/resources/datasets.md)

---

### 🎯 Benchmarks & Leaderboards

**Evaluation Tools:**
- **WorldLens** - Comprehensive evaluation framework for driving world models [![arXiv](https://img.shields.io/badge/arXiv-2512.10958-b31b1b.svg)](https://arxiv.org/abs/2512.10958)
- **VBench** - Video generation quality metrics [![arXiv](https://img.shields.io/badge/arXiv-2311.17982-b31b1b.svg)](https://arxiv.org/abs/2311.17982)
- **FVD** - Fréchet Video Distance for video quality
- **LPIPS** - Learned Perceptual Image Patch Similarity

> 🎯 For complete benchmarks and leaderboards, see [docs/resources/benchmarks.md](docs/resources/benchmarks.md)

---

### 🛠️ Tools & Libraries

**Frameworks:**
- **DreamerV3** - State-of-the-art model-based RL [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/danijar/dreamerv3)
- **Stable Diffusion** - Foundation for video generation models
- **PyTorch3D** - 3D deep learning library

**Simulation:**
- **CARLA** - Open-source driving simulator [![Website](https://img.shields.io/badge/Website-Link-blue)](https://carla.org/)
- **Isaac Sim** - NVIDIA robotics simulator
- **MuJoCo** - Physics engine for robotics

> 🛠️ For complete list of tools, see [docs/resources/tools.md](docs/resources/tools.md)

---

## 🌐 Community

### 🏆 Workshops & Challenges

- **CVPR 2025 Workshop on World Models** [![Website](https://img.shields.io/badge/Website-Link-blue)](https://world-models-workshop.github.io/)
- **ICCV 2025 Workshop on 4D World Models** - Bridging Generation and Reconstruction
- **OpenDriveLab Challenges** - Annual autonomous driving competitions

> 🏆 For complete list of workshops, see [docs/community/workshops.md](docs/community/workshops.md)

---

### 👥 Research Groups

**Leading Labs:**
- **NVIDIA Toronto AI Lab** - Cosmos, GAIA series
- **Wayve** - End-to-end driving with world models
- **Tesla AI** - FSD world model development
- **UC Berkeley RAIL** - Model-based RL research
- **DeepMind** - Genie, DreamerV3

> 👥 For complete list of research groups, see [docs/community/research-groups.md](docs/community/research-groups.md)

---

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**How to contribute:**
1. Fork the repository
2. Add your paper/resource following the format
3. Ensure all links are valid
4. Submit a pull request

**Format for papers:**
```markdown
| **Paper Title** | `Venue Year` | [![arXiv](badge)](url) [![Code](badge)](url) |
```

---

## 📜 Citation

If you find this repository useful, please consider citing:

```bibtex
@misc{awesome-world-models-2026,
  title={Awesome World Models: A Comprehensive Collection},
  author={Jing, Bowen},
  year={2026},
  howpublished={\url{https://github.com/Bowen12137/Awesome-World-Models}}
}
```

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Bowen12137/Awesome-World-Models&type=Date)](https://star-history.com/#Bowen12137/Awesome-World-Models&Date)

---

## 📊 Repository Statistics

### Overview

- **Total Papers**: 489
- **Starred Papers**: 74
- **Papers with Code**: 195 (40%)
- **Year Range**: 2012 - 2026
- **Top Venues**: CVPR (41), ICCV (16), ICLR (10)

### Visualizations

<div align="center">

#### Papers by Year
![Papers by Year](assets/images/papers_by_year.png)

#### Top Venues
![Top Venues](assets/images/top_venues.png)

#### Category Distribution
![Category Distribution](assets/images/category_distribution.png)

#### Resource Availability
![Resource Availability](assets/images/resource_availability.png)

</div>

**Last Updated**: March 6, 2026

---

<div align="center">

Made with ❤️ by the World Models community

[⬆ Back to Top](#-awesome-world-models)

</div>
