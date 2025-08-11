---
title: "Procedural Mistake Detection via Action Effect Modeling"
collection: publications
date: 2025-08-07
venue: "Under Review"
---
**Wenliang Guo**, Yiujiang Pu, Yu Kong

<!-- [[Paper](https://ieeexplore.ieee.org/document/9616415)] 
[[Code](https://github.com/WenliangGuo/HANUN)] -->
[[Website](https://wenliangguo.github.io/Mistake_Detection/)]

Abstract:Mistake detection in procedural tasks is essential for developing intelligent assistive agents that enhance learning and task execution. Existing methods predominantly focus on analyzing how an action is performed, while overlooking what it produces, i.e., the action effect. However, execution mistakes often manifest not in the action itself but in its outcome, such as an unintended object state or an incorrect spatial arrangement. To address this, we introduce Action Effect Modeling (AEM), a unified framework that jointly captures action execution and its effects from a causal perspective. AEM first identifies the outcome of an action by selecting the most informative effect frame based on semantic relevance and visual quality. It then extracts complementary cues from visual grounding and symbolic scene graphs, aligning them in a shared latent space to form robust effect-aware representations. To detect mistakes, we design a prompt-based detector that incorporates task-specific prompts and aligns each action segment with its intended execution semantics. Our approach outperforms prior work on the EgoPER and CaptainCook4D benchmarks under the challenging One-Class Classification (OCC) setting. These results highlight the importance of jointly modeling execution and effect for accurate mistake detection in real-world procedural tasks.