# World Models Taxonomy

This document is the authoritative classification spec for paper entries in this repository.

The goal is to make paper placement strict, stable, and contributor-friendly while preserving broad coverage of the field.

---

## 1. Scope

### Research is paper-only

The `Research` section in `README.md` is reserved for papers only:
- survey/review papers
- theory/foundation papers
- benchmark/evaluation papers
- primary research papers

The following do **not** belong in `Research`:
- talks and presentations
- tutorials and courses
- datasets
- tools, libraries, and simulators
- workshops and challenges
- research groups and labs
- forums, newsletters, Discord/Slack communities, and other community links

Those items belong in the dedicated `Learning Resources`, `Practical Resources`, and `Community` sections.

### One canonical home per paper

Every retained paper must appear in exactly one canonical place in `Research`.

Do **not** list the same paper under both a paradigm section and a domain section. Do **not** duplicate a paper because it fits multiple settings.

---

## 2. Canonical paper map

All papers in `Research` must be placed in one of these sections:

1. `Surveys & Reviews`
2. `Theory & Foundations`
3. `Benchmarks & Evaluation`
4. `Primary Research by Domain`
   - `General / Foundational`
   - `Autonomous Driving`
   - `Embodied AI & Robotics`
   - `Interactive Digital Environments`
   - `Social / Multi-Agent`
   - `Scientific World Models`

This is the only canonical paper map used by the repository.

---

## 3. Required classification fields

Each paper entry should be classified using these fields:

- `paper_type`
- `primary_domain`
- `primary_paradigm`
- `secondary_tags` (optional)

### Requiredness

- `paper_type` is required for **every** paper.
- `primary_domain` is required for **Primary Research** papers.
- `primary_paradigm` is required for **Primary Research** papers.
- `secondary_tags` are optional.

For `Survey/Review`, `Theory/Foundations`, and `Benchmark/Evaluation`, `primary_domain` and `primary_paradigm` may be omitted when the work is intentionally cross-domain or cross-paradigm. Do not force a fake single paradigm onto a broad survey or theory paper.

---

## 4. Allowed paper types

### 4.1 Survey/Review

Use `Survey/Review` when the paper's main contribution is synthesis rather than a new world-model method.

Typical signals:
- survey
- review
- taxonomy
- landscape/outlook
- comprehensive overview

Examples:
- surveys of world models for autonomous driving
- surveys of embodied world models
- broad 3D/4D world modeling surveys

### 4.2 Theory/Foundations

Use `Theory/Foundations` when the main contribution is conceptual, analytical, or foundational.

Typical signals:
- theoretical framing of world models
- representation/inductive-bias analysis
- interpretability or mechanistic understanding
- formal arguments about what makes a world model work

Examples:
- papers on physical grounding
- papers analyzing learned world models in transformers
- foundational agenda-setting papers

### 4.3 Benchmark/Evaluation

Use `Benchmark/Evaluation` when the main contribution is evaluating, stress-testing, or standardizing comparison of world models.

Typical signals:
- benchmark suite
- leaderboard
- evaluation protocol
- metric paper
- diagnostic testbed
- data engine or scenario suite whose main purpose is assessment

Examples:
- world-model benchmark papers
- evaluation metric papers
- systematic reliability or robustness test suites

### 4.4 Primary Research

Use `Primary Research` when the paper's main contribution is a new model, algorithm, training recipe, system, or integrated method.

Typical signals:
- introduces a new world model architecture
- proposes a new planning/training pipeline
- introduces a new generative simulation/control method
- presents a new action-conditioned world-model system

Most papers in the repository will fall into this class.

---

## 5. Allowed primary domains

Only use the following `primary_domain` values for `Primary Research` papers.

### 5.1 General / Foundational

Use when the paper is not anchored to a single downstream domain and is best read as a general world-model contribution.

Use this when:
- the paper is explicitly domain-agnostic
- the core claim is broad and foundational
- experiments span multiple settings without one clear target application
- the work is mainly about a reusable world-model capability

Do **not** use this just because a paper feels important. If the work is clearly aimed at driving, robotics, web agents, or science, use that domain instead.

### 5.2 Autonomous Driving

Use when the core evaluation setting or claimed target use case is self-driving.

Includes:
- future scene prediction for driving
- driving simulation
- planning for autonomous vehicles
- occupancy or sensor generation for driving stacks
- AD safety and long-tail scenario generation

### 5.3 Embodied AI & Robotics

Use when the core target is a physical agent acting in the world.

Includes:
- manipulation
- navigation
- locomotion
- mobile manipulation
- robotic planning and control
- VLA systems for robots
- sim-to-real robot learning

### 5.4 Interactive Digital Environments

Use when the paper is about interactive virtual environments rather than physical robots or real vehicles.

Includes:
- games
- game engines
- Minecraft and Atari environments
- XR and virtual environments
- browser/web-agent environments
- computer-use or software-interaction worlds

This is the canonical home for papers that might otherwise be split between game simulation and web agents.

### 5.5 Social / Multi-Agent

Use when the core target is modeling social interaction, human behavior, or multi-agent dynamics.

Includes:
- multi-agent coordination
- social navigation
- pedestrian/human behavior modeling
- theory-of-mind-style simulation
- social world-model environments

### 5.6 Scientific World Models

Use when the core target is scientific simulation or scientific discovery.

Includes:
- physics simulation
- biology and medicine
- chemistry and molecules
- climate and earth systems
- scientific forecasting or experiment design

---

## 6. Allowed primary paradigms

Only use the following `primary_paradigm` values for `Primary Research` papers.

### 6.1 Video-based

Use when the main predicted world state is image/video space or a video-generation latent tied directly to rendered frames.

Typical signals:
- next-frame / future video prediction
- diffusion or autoregressive video generation
- visually rendered rollout is the central output

### 6.2 3D Occupancy / 3D Scene

Use when the main predicted state is an explicit 3D scene representation.

Includes:
- occupancy grids
- voxel fields
- Gaussian splatting scene models
- NeRF-style scene rollouts
- explicit structured 3D world states

### 6.3 LiDAR / Point Cloud

Use when the main predicted state is LiDAR, range images, or point clouds.

### 6.4 Latent-State / Tokenized

Use when the main predicted state is a latent or tokenized internal state rather than explicit video, occupancy, or LiDAR output.

Typical signals:
- latent dynamics models
- token-based world models
- JEPA-style latent prediction
- sequence models over learned world tokens

### 6.5 Multimodal / World Foundation

Use when the paper's main contribution is a unified world model across multiple modalities and no single explicit state representation clearly dominates.

Typical signals:
- world foundation model framing
- joint modeling across multiple modalities/tasks
- one model intended to serve many observation and action interfaces

Do **not** use this just because the paper consumes multiple inputs. If one predicted state representation is clearly primary, use that representation instead.

### 6.6 Action-Conditioned / Policy-Centric

Use when the world-model contribution is tightly centered on control, decision-making, or policy learning, and the action-conditioned decision loop is the main novelty.

Typical signals:
- planning or RL is the core contribution
- the paper is best understood as a world model for action selection
- prediction exists mainly to support policy improvement or control

Do **not** use this for every paper that takes actions as input. If the main novelty is still video, 3D scene, or latent prediction, use that representation and add a task tag such as `planning/RL`.

---

## 7. Secondary tags

`secondary_tags` are optional. They help describe setting, task, or emphasis, but they do **not** determine canonical placement.

Recommended tags include:
- `VLA`
- `manipulation`
- `navigation`
- `locomotion`
- `planning/RL`
- `web-agent`
- `simulation`
- `safety`
- `sim-to-real`
- `language-conditioned`
- `multi-agent`
- `human-behavior`
- `physics`
- `biology`
- `medicine`

Rules:
- Use tags sparingly.
- Prefer 0-3 tags per paper.
- Tags are descriptive, not hierarchical.
- Tags never create new canonical sections.

In particular, `VLA`, `navigation`, `locomotion`, `web-agent`, and `planning/RL` are **tags**, not top-level paper categories.

---

## 8. Tie-break rules

### 8.1 Choose `paper_type` by dominant contribution

Use the paper for what it is mainly trying to contribute.

Priority guidance:
1. If the paper mainly synthesizes prior work, use `Survey/Review`.
2. If it mainly defines evaluation, metrics, or benchmarking infrastructure, use `Benchmark/Evaluation`.
3. If it mainly advances conceptual or theoretical understanding, use `Theory/Foundations`.
4. Otherwise, use `Primary Research`.

### 8.2 Choose `primary_domain` by core evaluation setting

For `Primary Research`, choose domain by the paper's main target use case and evaluation setting.

Ask:
- Where is the method primarily tested?
- What deployment setting does the abstract claim?
- What users or agents is the paper actually trying to help?

Examples:
- a robot manipulation paper with VLA framing still belongs in `Embodied AI & Robotics`
- a browser-agent world model belongs in `Interactive Digital Environments`
- a social navigation paper belongs in `Social / Multi-Agent` only if social interaction is the central claim, not merely a detail of robot evaluation

### 8.3 Choose `primary_paradigm` by predicted state representation

Choose paradigm by what the model mainly rolls out or predicts, not by every input/output it touches.

Examples:
- camera input + occupancy rollout -> `3D Occupancy / 3D Scene`
- multimodal input + latent rollout -> `Latent-State / Tokenized`
- action-conditioned video prediction for driving -> `Video-based`

### 8.4 VLA is not a domain

Vision-language-action is a model setting, not a canonical domain.

- robot VLA papers -> `Embodied AI & Robotics` + tag `VLA`
- web-agent VLA-like papers -> `Interactive Digital Environments` + tag `web-agent`

### 8.5 Planning/RL is not a domain

Planning and RL are task emphases.

- driving planning papers stay in `Autonomous Driving`
- robot policy-learning papers stay in `Embodied AI & Robotics`
- use `planning/RL` as a tag when helpful

### 8.6 Web-agent papers belong with digital environments

Do not split web-agent papers into ad hoc sections. Their canonical home is `Interactive Digital Environments`.

### 8.7 Social papers must be socially central

Use `Social / Multi-Agent` only when social or multi-agent interaction is the paper's main object of modeling. If a driving or robotics paper merely contains other agents, that alone is not enough.

### 8.8 Scientific papers must be scientifically central

Use `Scientific World Models` only when the scientific domain is the actual target use case. A general method evaluated on one science dataset does not automatically move there.

### 8.9 Non-paper resources never stay in `Research`

If an item is a workshop, challenge, blog post, course, dataset page, tool, library, or research group, move it out of `Research` even if it is useful.

---

## 9. Duplicate policy

### 9.1 No duplicate canonical entries

A paper may appear only once in canonical `Research`.

### 9.2 No duplicate arXiv IDs

If two entries share the same arXiv ID, they should usually be treated as the same paper unless there is a clear reason otherwise.

### 9.3 No duplicate titles for the same underlying work

If a published version and arXiv version refer to the same paper, keep one canonical entry.

Preferred handling:
- keep the most stable public title
- keep the strongest venue label available
- keep arXiv/code/website links together in the same row when available

### 9.4 Distinct sequels are allowed

Series such as `DriveDreamer` and `DriveDreamer-2` are separate papers when they are genuinely distinct works.

---

## 10. Submission checklist

Before adding a paper, confirm all of the following:

- it is actually a paper, not only a project page or workshop
- it fits the repository scope
- `paper_type` is selected
- if `Primary Research`, `primary_domain` is selected
- if `Primary Research`, `primary_paradigm` is selected
- optional tags are used only when they add clarity
- the paper does not duplicate an existing title or arXiv ID
- the paper has exactly one canonical home in `Research`
- links are valid

---

## 11. Worked examples

| Paper | paper_type | primary_domain | primary_paradigm | secondary_tags |
|------|------------|----------------|------------------|----------------|
| DriveDreamer | Primary Research | Autonomous Driving | Video-based | simulation |
| OccWorld | Primary Research | Autonomous Driving | 3D Occupancy / 3D Scene | planning/RL |
| Genie | Primary Research | Interactive Digital Environments | Video-based | simulation |
| DreamerV3 | Primary Research | General / Foundational | Action-Conditioned / Policy-Centric | planning/RL |
| Web World Models | Primary Research | Interactive Digital Environments | Video-based or Multimodal / World Foundation, depending on the paper's main rollout target | web-agent |
| WorldLens | Benchmark/Evaluation | optional | optional | safety |
| A Survey of Embodied World Models | Survey/Review | optional | optional | |
| Inductive Biases Guide Learned World Models in Transformers | Theory/Foundations | optional | optional | |

When a case is ambiguous, prefer the most defensible single interpretation and document that choice consistently.

---

## 12. Maintainer note

This taxonomy is intentionally strict:
- one paper, one canonical home
- one dominant paper type
- one primary domain for primary research
- one primary paradigm for primary research

Strictness is what allows outside contributors to classify papers consistently without creating overlapping sections over time.

---

**Last Updated**: April 7, 2026
