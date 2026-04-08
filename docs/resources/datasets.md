# Datasets for World Models

Curated datasets for world models research, organized by application domain.

> For evaluation suites and metrics, see [benchmarks.md](benchmarks.md).

---

## 🚗 Autonomous Driving Datasets

### Large-Scale Multi-Modal Datasets

| Dataset | Scale | Modalities | Tasks | Year | Resources |
|---------|-------|------------|-------|------|-----------|
| **nuScenes** | 1000 scenes, 1.4M images | Camera, LiDAR, Radar, GPS/IMU | Detection, Tracking, Prediction, Occupancy | 2019 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.nuscenes.org/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/1903.11027) |
| **Waymo Open Dataset** | 1000 segments, 200k frames | Camera, LiDAR | Detection, Tracking, Motion Forecasting | 2019 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://waymo.com/open/) [![Paper](https://img.shields.io/badge/Paper-CVPR-blue)](https://openaccess.thecvf.com/content_CVPR_2020/html/Sun_Scalability_in_Perception_for_Autonomous_Driving_Waymo_Open_Dataset_CVPR_2020_paper.html) |
| **KITTI** | 15k frames | Camera, LiDAR, GPS/IMU | Detection, Tracking, Odometry, Depth | 2012 | [![Website](https://img.shields.io/badge/Website-Link-blue)](http://www.cvlibs.net/datasets/kitti/) [![Paper](https://img.shields.io/badge/Paper-CVPR-blue)](http://www.cvlibs.net/publications/Geiger2012CVPR.pdf) |
| **Argoverse 2** | 1000 scenarios | Camera, LiDAR | Detection, Tracking, Forecasting | 2021 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.argoverse.org/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.00493) |
| **ONCE** | 1M frames, 7k scenes | Camera, LiDAR | Detection, Tracking | 2021 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://once-for-auto-driving.github.io/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2106.11037) |

### Occupancy & 3D Scene Understanding

| Dataset | Scale | Modalities | Tasks | Year | Resources |
|---------|-------|------------|-------|------|-----------|
| **Occ3D** | 16k frames | Camera, LiDAR | 3D Occupancy Prediction | 2023 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://tsinghua-mars-lab.github.io/Occ3D/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14365) |
| **OpenOccupancy** | nuScenes-based | Camera, LiDAR | Semantic Occupancy | 2023 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/JeffWang987/OpenOccupancy) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.03991) |
| **SurroundOcc** | 28k frames | Camera | 3D Occupancy | 2023 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/weiyithu/SurroundOcc) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09551) |

### Simulation & Scenario Generation

| Dataset | Scale | Modalities | Tasks | Year | Resources |
|---------|-------|------------|-------|------|-----------|
| **CARLA** | Unlimited (Simulator) | Camera, LiDAR, Radar, GPS | End-to-end Driving, Planning | 2017 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://carla.org/) [![Paper](https://img.shields.io/badge/Paper-CoRL-blue)](http://proceedings.mlr.press/v78/dosovitskiy17a.html) |
| **nuPlan** | 1500 hours | Camera, LiDAR | Planning, Simulation | 2021 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.nuscenes.org/nuplan) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2106.11810) |
| **NAVSIM** | 850 scenes | Camera, LiDAR | Planning Benchmark | 2024 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/autonomousvision/navsim) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15349) |

---

## 🤖 Embodied AI & Robotics Datasets

### Manipulation Datasets

| Dataset | Scale | Modalities | Tasks | Year | Resources |
|---------|-------|------------|-------|------|-----------|
| **CALVIN** | 24k trajectories | RGB, Depth, Proprioception | Language-conditioned Manipulation | 2021 | [![Website](https://img.shields.io/badge/Website-Link-blue)](http://calvin.cs.uni-freiburg.de/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.03227) [![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/mees/calvin) |
| **RoboNet** | 15M frames, 113 robots | RGB | Multi-robot Manipulation | 2019 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.robonet.wiki/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/1910.11215) |
| **RoboCasa** | 100k trajectories | RGB, Depth | Kitchen Manipulation | 2024 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robocasa.ai/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.02523) |
| **RT-1 Dataset** | 130k episodes | RGB | Real-world Manipulation | 2022 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robotics-transformer1.github.io/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.06817) |
| **Open X-Embodiment** | 1M+ trajectories, 22 robots | RGB, Depth, Proprioception | Multi-task Manipulation | 2023 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://robotics-transformer-x.github.io/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08864) |

### Navigation Datasets

| Dataset | Scale | Modalities | Tasks | Year | Resources |
|---------|-------|------------|-------|------|-----------|
| **Habitat-Matterport 3D** | 90 scenes | RGB, Depth | Indoor Navigation | 2019 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://aihabitat.org/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/1807.06757) |
| **Gibson** | 572 scenes | RGB, Depth | Indoor Navigation | 2018 | [![Website](https://img.shields.io/badge/Website-Link-blue)](http://gibsonenv.stanford.edu/) [![Paper](https://img.shields.io/badge/Paper-CVPR-blue)](https://openaccess.thecvf.com/content_cvpr_2018/html/Xia_Gibson_Env_Real-World_CVPR_2018_paper.html) |

---

## 🎮 Game & Simulation Datasets

| Dataset | Scale | Modalities | Tasks | Year | Resources |
|---------|-------|------------|-------|------|-----------|
| **Atari 2600** | 57 games | RGB | RL Benchmark | 2013 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/openai/gym) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/1207.4708) |
| **Minecraft** | Unlimited (Procedural) | RGB, Voxels | Open-world Exploration | - | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://www.minecraft.net/) |
| **MineRL** | 60M frames | RGB, Actions | Minecraft RL | 2019 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://minerl.io/) [![Paper](https://img.shields.io/badge/Paper-NeurIPS-blue)](https://arxiv.org/abs/1907.13440) |
| **DeepMind Lab** | Multiple levels | RGB | 3D Navigation & Puzzles | 2016 | [![Website](https://img.shields.io/badge/Website-Link-blue)](https://github.com/deepmind/lab) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/1612.03801) |

---

## 🔬 Scientific & Specialized Datasets

### Physics Simulation

| Dataset | Scale | Modalities | Tasks | Year | Resources |
|---------|-------|------------|-------|------|-----------|
| **PhysDiff** | 10k simulations | Video | Physics Prediction | 2023 | [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.10309) |
| **CLEVRER** | 20k videos | Video | Physical Reasoning | 2020 | [![Website](https://img.shields.io/badge/Website-Link-blue)](http://clevrer.csail.mit.edu/) [![Paper](https://img.shields.io/badge/Paper-ICLR-blue)](https://arxiv.org/abs/1910.01442) |

### Medical & Healthcare

| Dataset | Scale | Modalities | Tasks | Year | Resources |
|---------|-------|------------|-------|------|-----------|
| **Medical Segmentation Decathlon** | 2633 3D images | CT, MRI | Multi-organ Segmentation | 2018 | [![Website](https://img.shields.io/badge/Website-Link-blue)](http://medicaldecathlon.com/) [![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/1902.09063) |

---

## 🔗 Dataset Collections

- **[Awesome Autonomous Driving Datasets](https://github.com/autonomousvision/awesome-autonomous-driving-datasets)** - Curated list of AD datasets
- **[Robotics Datasets](https://github.com/mint-lab/awesome-robotics-datasets)** - Collection of robotics datasets
- **[Papers with Code Datasets](https://paperswithcode.com/datasets)** - ML datasets with benchmarks
- **[Hugging Face Datasets](https://huggingface.co/datasets)** - Open-source dataset hub

---

**Last Updated**: April 2026
