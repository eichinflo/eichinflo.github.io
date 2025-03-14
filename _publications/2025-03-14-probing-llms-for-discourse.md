---
title: "Probing LLMs for Multilingual Discourse Generalization Through a Unified Label Set"
collection: publications
permalink: /publication/2025-03-14-probing-llms
excerpt: 'Probing large language models for multilingual discourse relation information unifying framework-specific label sets.'
date: 2025-03-14
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2503.10515'
---

Discourse understanding is essential for many NLP tasks, yet most existing work remains constrained by framework-dependent discourse representations. This work investigates whether large language models (LLMs) capture discourse knowledge that generalizes across languages and frameworks. We address this question along two dimensions: (1) developing a unified discourse relation label set to facilitate cross-lingual and cross-framework discourse analysis, and (2) probing LLMs to assess whether they encode generalizable discourse abstractions. Using multilingual discourse relation classification as a testbed, we examine a comprehensive set of 23 LLMs of varying sizes and multilingual capabilities. Our results show that LLMs, especially those with multilingual training corpora, can generalize discourse information across languages and frameworks. Further layer-wise analyses reveal that language generalization at the discourse level is most salient in the intermediate layers. Lastly, our error analysis provides an account of challenging relation classes.

You can find the preprint on [arXiv](https://arxiv.org/abs/2503.10515) and code on [GitHub](https://github.com/mainlp/discourse_probes).