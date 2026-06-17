---
title: "ExPLAIND: Unifying Model, Data, and Training Attribution to Study Model Behavior"
collection: publications
permalink: /publication/2025-05-26-grokking-explaind
excerpt: 'We introduce ExPLAIND — an interpretability framework for jointly attributing model components, data, and training dynamics and apply it to investigate Grokking.'
date: 2026-06-17
venue: 'ICML 2026'
paperurl: 'https://icml.cc/virtual/2026/poster/66073'
authors: '<b>Florian Eichin</b>, Yupei Du, Philipp Mondorf, Maria Matveev, Barbara Plank, and Michael A. Hedderich'
---

Post-hoc interpretability methods typically attribute a model’s behavior to its components, data, or training trajectory in isolation, and are often tied to a particular level of granularity along the local-to-global spectrum. This leads to explanations that lack a unified view and may miss key interactions. We present ExPLAIND, a theoretically grounded, unified framework that integrates model components, data, and training trajectory while supporting explanations across granularities. We generalize recent work on gradient path kernels, reformulating models trained by AdamW as kernel machines. From the resulting kernel feature maps, we derive novel parameter-wise and step-wise influence scores. We empirically validate the resulting decomposition of model behavior in several settings and apply ExPLAIND to two case studies. Our findings on a Transformer exhibiting Grokking support previously proposed learning phases, while refining the final phase as one in which outer layers align around a representation pipeline learned after memorization. For EuroLLM pretraining, ExPLAIND reveals a two-phase dynamic, with the first characterized by outer-layer MLP learning and the second by increased relative influence of intermediate attention layers. These results establish ExPLAIND as a unified framework for interpreting model behavior and training dynamics.

You can find the paper on [arXiv](https://arxiv.org/abs/2505.20076) and on [the ICML homepage](https://icml.cc/virtual/2026/poster/66073). This paper will also be presented at the [Mechanistic Interpretability Workshop](https://openreview.net/forum?id=VOqomYvKEb). 

**Want to use ExPLAIND?** Our implementation can be found on [GitHub](https://github.com/mainlp/explaind).