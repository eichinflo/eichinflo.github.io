---
title: "Interpreting Translation Dynamics in Multilingual Pretraining"
collection: talks
type: "Talk"
permalink: /talks/2026-04-20-edinburgh
venue: "University of Edinburgh, ILCC"
date: 2026/04/20
location: "Edinburgh"
description: "A talk on explaining multilingual pretraining."
---

[Felicia](https://koernerfelicia.github.io) and I are invited to the [ILCC, University of Edinburgh](https://informatics.ed.ac.uk/ilcc/news-events/upcoming-seminars) to talk about our latest work on multilingual pretraining.

Abstract: Post-hoc interpretability methods typically attribute a model's behavior to its components, data, or training trajectory in isolation. This leads to explanations that lack a unified view and may miss key interactions. While combining existing methods or applying them at different training stages offers broader insights, such approaches usually lack theoretical support. To address this, we present ExPLAIND, a unified framework that integrates all these perspectives. First, we generalize recent work on gradient path kernels, which reformulate models trained by gradient descent as a kernel machine, to realistic settings like AdamW. We empirically validate that a CNN and a Transformer are accurately replicated by this reformulation. Second, we derive novel parameter- and step-wise influence scores from the kernel feature maps. Finally, jointly interpreting model components and data over the training process, we leverage ExPLAIND to analyze a Transformer that exhibits Grokking. Our findings support previously proposed stages of Grokking, while refining the final phase as one of alignment of input embeddings and final layers around a representation pipeline learned after the memorization phase.

