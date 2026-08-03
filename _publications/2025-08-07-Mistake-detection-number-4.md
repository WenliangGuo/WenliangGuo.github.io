---
title: "Procedural Mistake Detection via Action Effect Modeling"
collection: publications
date: 2026-01-25
venue: 'ICLR'
badge: "ICLR'26"
image: publications/AEM.png
paperurl: 'https://arxiv.org/abs/2512.03474'
code: 'https://github.com/WenliangGuo/AEM'
website: 'https://wenliangguo.github.io/Mistake_Detection/'
---
**Wenliang Guo**, Yiujiang Pu, Yu Kong

[[Paper](https://arxiv.org/abs/2512.03474)] 
[[Code](https://github.com/WenliangGuo/AEM)]
[[Website](https://wenliangguo.github.io/Mistake_Detection/)]

Abstract: Mistake detection in procedural tasks is essential for building intelligent systems that support learning and task execution. Existing approaches primarily analyze how an action is performed, while overlooking what it produces, i.e., the action effect. Yet many errors manifest not in the execution itself but in the resulting outcome, such as an unintended object state or incorrect spatial arrangement. To address this gap, we propose Action Effect Modeling (AEM), a unified framework that jointly captures action execution and its outcomes through a probabilistic formulation. AEM first identifies the outcome of an action by selecting the most informative effect frame based on semantic relevance and visual quality. It then extracts complementary cues from visual grounding and symbolic scene graphs, aligning them in a shared latent space to form robust effect-aware representations. To detect mistakes, we further design a prompt-based detector that incorporates task-specific prompts and aligns each action segment with its intended execution semantics. Our approach achieves state-of-the-art performance on the EgoPER and CaptainCook4D benchmarks under the challenging one-class classification (OCC) setting. These results demonstrate that modeling both execution and outcome yields more reliable mistake detection, and highlight the potential of effect-aware representations to benefit a broader range of downstream applications.
