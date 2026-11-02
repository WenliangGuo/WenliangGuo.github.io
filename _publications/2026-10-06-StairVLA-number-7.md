---
title: "StairVLA: Stage-Aware Hierarchical Action Generation for Vision-Language-Action Models"
collection: publications
date: 2026-10-06
venue: 'arXiv preprint'
badge: "arXiv'26"
image: publications/stairvla-framework.png
paperurl: 'https://arxiv.org/abs/2610.07756'
code: 'https://github.com/Dicomsky/StairVLA'
website: 'https://dicomsky.github.io/projects/stairvla/'
---
Shangyuan Yuan, Xinda Qi, Yujiang Pu, **Wenliang Guo**, Xiaobo Tan

[[Paper](https://arxiv.org/abs/2610.07756)]
[[Code](https://github.com/Dicomsky/StairVLA)]
[[Website](https://dicomsky.github.io/projects/stairvla/)]

Summary: StairVLA speeds up vision-language-action models by dividing action generation into two stages. A high-level model creates a partially denoised plan that can be reused across control cycles, while a lightweight refiner updates each local action chunk with fresh visual observations. This hierarchy reduces computation while retaining frequent feedback from the environment. Experiments with two VLA backbones, simulated benchmarks, and real robots show lower inference cost with strong task performance. On LIBERO, the GR00T-based model reaches 97.8% average success, compared with 96.5% for its baseline, and reduces amortized latency per action chunk from 115.0 ms to 44.2 ms.
