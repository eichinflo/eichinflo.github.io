---
title: "Don't Forget! Decomposing the Training Dynamics of Memorization in Language Models"
collection: publications
permalink: /publication/2026-09-29-dont-forget-memorization-dynamics
excerpt: 'We decompose LLM loss trajectories to characterize memorization training dynamics through gradient alignment and validate our results through early memorization prediction causal post-hoc ablation.'
date: 2026-09-29
venue: 'Preprint'
paperurl: 'https://arxiv.org/abs/2609.34933'
authors: '<b>Florian Eichin</b>, Philipp Mondorf, Andrei Mircea, Yupei Du, Barbara Plank, Michael A. Hedderich'
---

Memorization has been proposed as a mechanism to explain how language models fit the tail of their training distributions, but its training dynamics are not understood well. In this work, we take a fine-grained look at memorization by decomposing the loss trajectory of memorized sequences over training and model parameters. Across the Pythia family, we study memorization of duplicated training sequences (recitation) and rare ones (recollection). We find that memorization in both cases is characterized by sequence-level gradient alignment, though recitation suffers from misalignment with other training influences which causes forgetting, explaining the necessity for higher duplication of these examples. We further show that the lower model layers are the most involved in memorization and forgetting. Predicting memorization, our decomposition improves over a cross-entropy baseline, especially in larger models and early in training. Intervening on a small set of highly influential parameters we are able to ablate memorization in the final model. Together, these findings advance our understanding of how memorization develops during training and offer insights for predicting and intervening on it.

Preprint is live on [arXiv](https://arxiv.org/abs/2609.34933). We release our code upon publication.