---
title: "Semantic Component Analysis: Introducing Multi-Topic Distributions to Clustering-Based Topic Modeling"
collection: publications
permalink: /publication/2024-10-28-semantic-components
excerpt: 'We introduce multi-topic distributions to the clustering-based topic modeling pipeline and reduce the number of samples assigned to noise to zero.'
date: 2024-10-28
venue: 'EMNLP 2025 Findings'
paperurl: 'https://arxiv.org/abs/2410.21054'
authors: '<b>Florian Eichin</b>, Carolin M. Schuster, Georg Groh, and Michael A. Hedderich'
---

Topic modeling is a key method in text analysis, but existing approaches fail to efficiently scale to large datasets or are limited by assuming one topic per document. Overcoming these limitations, we introduce Semantic Component Analysis (SCA), a topic modeling technique that discovers multiple topics per sample by introducing a decomposition step to the clustering-based topic modeling framework. We evaluate SCA on Twitter datasets in English, Hausa and Chinese. There, it achieves competetive coherence and diversity compared to BERTopic, while uncovering at least double the topics and maintaining a noise rate close to zero. We also find that SCA outperforms the LLM-based TopicGPT in scenarios with similar compute budgets. SCA thus provides an effective and efficient approach for topic modeling of large datasets.


You can find the preprint on [arXiv](https://arxiv.org/abs/2410.21054) and code on [GitHub](https://github.com/mainlp/semantic_components).