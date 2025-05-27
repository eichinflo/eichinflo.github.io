---
title: "Grokking ExPLAIND: Unifying Model, Data, and Training Attribution to Study Model Behavior"
collection: publications
permalink: /publication/2025-05-26-grokking-explaind
excerpt: 'We introduce ExPLAIND — an interpretability framework for jointly attributing model components, data, and training dynamics and apply it to investigate Grokking.'
date: 2025-05-26
venue: 'arXiv:2505.20076'
paperurl: 'https://arxiv.org/abs/2505.20076'
authors: '<b>Florian Eichin</b>, Yupei Du, Philipp Mondorf, Barbara Plank, and Michael A. Hedderich'
---

Post-hoc interpretability methods typically attribute a model’s behavior to its components, data, or training trajectory in isolation. This leads to explanations that lack a unified view and may miss key interactions. While combining existing methods or applying them at different training stages offers broader insights, these approaches usually lack theoretical support. In this work, we present ExPLAIND, a unified framework that integrates all three perspectives. First, we generalize recent work on gradient path kernels, which reformulate models trained by gradient descent as a kernel machine, to more realistic training settings. Empirically, we find that both a CNN and a Transformer model are replicated accurately by this reformulation. Second, we derive novel parameter- and step-wise influence scores from the kernel feature maps. We show their effectiveness in parameter pruning that is comparable to existing methods, reinforcing their value for model component attribution. Finally, jointly interpreting model components and data over the training process, we leverage ExPLAIND to analyze a Transformer that exhibits Grokking. Among other things, our findings support previously proposed stages of Grokking, while refining the final phase as one of alignment of input embeddings and final layers around a representation pipeline learned after the memorization phase. Overall, ExPLAIND provides a theoretically grounded, unified framework to interpret model behavior and training dynamics.

You can find the preprint on [arXiv](https://arxiv.org/abs/2505.20076) and code on [GitHub](https://github.com/mainlp/explaind).