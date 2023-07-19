---
title: "State-Enhanced Procedure Planning in Instructional Videos"
collection: publications
date: 2023-05-25
venue: 'Preprint'
---
Yulei Niu, **Wenliang Guo**, Long Chen, Xudong Lin, Shih-Fu Chang

[[Paper](https://openreview.net/forum?id=5FeRi11ARd)] 

Abstract: We study the problem of procedure planning in instructional videos, which requires the agent to produce a sequence of instruction steps to achieve a goal given the visual state observations. Recent works succeed in utilizing only action step annotations without state annotations, which leaves an open question about how the state information should be represented and utilized. In this work, we proposed to enhance state representation and reasoning for procedure planning. For state representation, we leveraged large language models (i.e., GPT-3) to describe the state changes of steps, which guides state representation learning via cross-modal contrastive learning. For state reasoning, we break up procedure planning into subproblems of subgoal decomposition and action step prediction, and use the generated state descriptions as external memory of Transformer models. We further conduct experimental analysis on the CrossTask and COIN benchmark datasets to demonstrate that our proposed state representation and reasoning methods not only promote procedure planning, but can conduct explainable state understanding.