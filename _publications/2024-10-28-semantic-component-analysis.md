---
title: "Semantic Component Analysis: Discovering Patterns in Short Texts Beyond Topics"
collection: publications
permalink: /publication/2024-10.28
excerpt: 'Finding detailed patterns in neural representations.'
date: 2021-10-05
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2410.21054'
---

Topic modeling is a key method in text analysis, but existing approaches are limited by assuming one topic per document or fail to scale efficiently for large, noisy datasets of short texts. We introduce Semantic Component Analysis (SCA), a novel topic modeling technique that overcomes these limitations by discovering multiple, nuanced semantic components beyond a single topic in short texts which we accomplish by introducing a decomposition step to the clustering-based topic modeling framework. Evaluated on multiple Twitter datasets, SCA matches the state-of-the-art method BERTopic in coherence and diversity, while uncovering at least double the semantic components and maintaining a noise rate close to zero while staying scalable and effective across languages, including an underrepresented one.

You can find the preprint on [arXiv](https://arxiv.org/abs/2410.21054) and code on [GitHub](https://github.com/mainlp/semantic_components).