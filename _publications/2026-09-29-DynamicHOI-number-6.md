---
title: "DynamicHOI: Coupled Dynamics for Physics-aware HOI Reconstruction"
collection: publications
date: 2026-09-29
venue: 'arXiv preprint'
badge: "arXiv'26"
image: publications/dynamichoi.jpg
paperurl: 'https://arxiv.org/abs/2609.36454'
website: 'https://wenliangguo.github.io/HOI-Reconstruction-Page/'
---
**Wenliang Guo**, Zhanbo Huang, Yu Kong

[[Paper](https://arxiv.org/abs/2609.36454)] 
[[Website](https://wenliangguo.github.io/HOI-Reconstruction-Page/)]

Abstract: We study hand-object interaction (HOI) reconstruction from monocular RGB videos, where partial observations can produce visually plausible yet mechanically inconsistent trajectories. Existing methods mainly enforce visual and geometric agreement, leaving the underlying interaction dynamics insufficiently constrained. We propose DynamicHOI, a physics-aware HOI reconstruction framework combining geometry-grounded diffusion refinement with coupled hand-object dynamics. Geometry spatially grounds visual evidence for trajectory refinement, while articulated inverse dynamics and Newton-Euler dynamics derive hand generalized forces and object wrenches for dynamics-level supervision. We further couple hand and object dynamics through contact-force transfer and recover active hand actuation as an interaction-level physical quantity. We formulate its empirical magnitude distribution into a probabilistic prior that penalizes unlikely actuation and suppresses mechanically implausible reconstructed motion. Experiments on three HOI datasets show consistent improvements in both hand and object reconstruction. The reconstructed trajectories further benefit downstream applications including hand world-model generation and robotic manipulation learning, demonstrating the value of physics-aware HOI modeling beyond reconstruction.
