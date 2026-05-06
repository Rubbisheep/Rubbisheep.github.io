---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<a id="about"></a>

## About Me

Hi, I'm **Mingyi Deng (邓明熠)**, currently an MStat student at the **University of Hong Kong (HKU)**. Before HKU, I received my B.S. from the **School of Statistics, Renmin University of China (RUC)** in the Data Science + Applied Economics dual-degree honors program.

My research focuses on **LLM-based agents**, especially **interactive and user-centric agents** — how agents recognize ambiguity, ask clarifying questions, and learn from multi-turn user feedback. I'm a research intern at **DeepWisdom (深度赋智)**, working on agent benchmarks, reinforcement learning for multi-turn agents, and agent framework design.

Feel free to reach me at **dengmingyi1219@163.com**.

<a id="Publications"></a>

## Publications

See the [Publications page]({{ base_path }}/publications/) for the full list. Selected work:

- **[InteractComp: Evaluating Search Agents With Ambiguous Queries]({{ base_path }}/publication/2025-10-28-interactcomp)** &nbsp; *(ICML 2026, first author)* — A benchmark of 210 expert-verified questions across 9 domains for evaluating whether search agents can recognize query ambiguity and actively interact to resolve it. Shows that while frontier LLMs improve rapidly on standard tasks, interactive disambiguation capability has stagnated. With Claude-sonnet-4, GPT-5, and commercial products evaluated.
- **[InfoPO: Information-Driven Policy Optimization for User-Centric Agents]({{ base_path }}/publication/2026-02-28-infopo)** &nbsp; *(ICML 2026)* — Turns per-turn information progress (vs. a masked-observation counterfactual) into a dense learning signal for multi-turn RL, combined with outcome reward to stabilize training under sparse/delayed rewards.
- **[ReCode: Unify Plan and Action for Universal Granularity Control]({{ base_path }}/publication/2025-10-27-recode)** — Unifies planning and action as executable code, with universal granularity control. +20.9% avg. relative gain over the strongest baseline on ALFWorld / ScienceWorld / WebShop, while cutting inference cost by 79–84%.

<a id="Educations"></a>

## Education

**The University of Hong Kong** &nbsp;—&nbsp; *Hong Kong SAR* &nbsp;·&nbsp; Aug 2025 – Dec 2026
MStat, Faculty of Computing and Data Science
Master of Statistics (admission rate ~9%; QS subject ranking top 25 globally).

**Renmin University of China** &nbsp;—&nbsp; *Beijing, China* &nbsp;·&nbsp; Sep 2020 – Jul 2024
B.S., School of Statistics
Data Science + Applied Economics dual-degree honors program (cohort of 10, ~4% selection rate).

<a id="Internships"></a>

## Internships

**DeepWisdom (深度赋智) — Research Intern** &nbsp;·&nbsp; Shenzhen &nbsp;·&nbsp; Jul 2025 – Jan 2026

- **Interactive agent evaluation and training.** Built the multi-turn interaction environment and evaluation pipeline for *InteractComp*; set up unified comparison of GPT-5 and Claude-series models under realistic ambiguous-query scenarios.
- **RL for multi-turn agents.** Integrated *InteractComp* and other interactive benchmarks into a `verl`-based RL framework for the *InfoPO* project, following a GRPO-style training recipe inspired by UserRL; designed rewards and debugged training stability under sparse rewards and non-discriminative batches.
- **Agent frameworks and trajectory data.** Contributed to *ReCode* and *AutoAppWorld*; reproduced ReAct / CodeAct, built multi-environment agent trajectory data, and ran SFT training plus inference-cost analysis.

**Nanjing Xuming Private Fund Management — Quant Research Intern** &nbsp;·&nbsp; Shenzhen &nbsp;·&nbsp; Feb 2025 – May 2025

- **Baseline model optimization.** Redesigned the original XGBoost pipeline, cutting training time from 23h to 4h; led the design of a two-stage quant model architecture achieving 80%+ relative win rate over the baseline across 56 label targets.
- **Factor selection.** Used LightGBM with feature importance, SHAP values, and 98%-cumulative-importance thresholds to improve quant factor selection; backtests significantly outperformed the original selection logic.
- **Tree + NN composite model.** Exploiting the weak correlation between tree models and neural networks, built a composite XGBoost + NN quant model; A/B tests showed significant full-period gains over single-model baselines.
- **Agent-driven quant exploration.** Built an initial *Agent-Quant* prototype on top of OpenManus-AutoQuant and Deepfund, using a three-tier role-based agent system for self-improving strategy design.

## Skills

- **Languages:** Python, C++, SQL
- **Frameworks:** PyTorch, TensorFlow, MetaGPT, OpenManus, OpenHands, smolagent
- **Tools:** Linux, Git, Conda, Docker
- **Human languages:** Chinese (native), English (IELTS 7.0)
