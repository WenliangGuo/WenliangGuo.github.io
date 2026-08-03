---
title: "ProcObject-10K: Benchmarking Object-Centric Procedural Understanding in Instructional Videos"
collection: publications
date: 2025-12-03
venue: 'arXiv preprint'
badge: "arXiv'25"
image: publications/procobject-10k.png
paperurl: 'https://arxiv.org/abs/2512.03479'
---
**Wenliang Guo**, Yu Kong

[[Paper](https://arxiv.org/abs/2512.03479)]

Abstract: Procedural activities are fundamentally driven by object state transitions, yet existing instructional video benchmarks remain action-centric and cannot evaluate whether models reason about how objects evolve toward task completion. In this work, we introduce ProcObject-10K, the first benchmark that jointly evaluates object-centric reasoning and temporal evidence grounding in instructional videos, across both egocentric and exocentric views. It comprises 10,522 open-ended VideoQA pairs grounded in 1,799 video clips, spanning 137 tasks across 9 domains and five reasoning types covering preconditions, state evolution, counterfactuals, mistakes, and readiness. Benchmarking 13 leading MLLMs reveals a substantial answering-grounding gap: models produce plausible answers while failing to localize the supporting evidence (mIoU < 45%), exposing their reliance on linguistic priors rather than fine-grained object dynamics. As a step toward closing this gap, we further provide an object-centric supervised fine-tuning baseline with pseudo object-level supervision and spatial-temporal constraints. Models fine-tuned on ProcObject-10K not only improve on the benchmark itself, but also transfer effectively to other grounded VideoQA and embodied planning tasks. The dataset, annotations, and evaluation toolkit will be publicly released to support future research on object-centric procedural understanding.
