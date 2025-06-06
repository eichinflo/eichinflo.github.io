---
title: "Semantic Component Analysis: Discovering Patterns in Short Texts Beyond Topics"
collection: publications
permalink: /publication/2024-10-28-semantic-components
excerpt: 'We introduce multi-topic distributions to the clustering-based topic modeling pipeline and reduce the number of samples assigned to noise to zero.'
date: 2024-10-28
venue: 'arXiv:2410.21054'
paperurl: 'https://arxiv.org/abs/2410.21054'
authors: '<b>Florian Eichin</b>, Carolin M. Schuster, Georg Groh, and Michael A. Hedderich'
---

Topic modeling is a key method in text analysis, but existing approaches are limited by assuming one topic per document or fail to scale efficiently for large, noisy datasets of short texts. We introduce Semantic Component Analysis (SCA), a novel topic modeling technique that overcomes these limitations by discovering multiple, nuanced semantic components beyond a single topic in short texts which we accomplish by introducing a decomposition step to the clustering-based topic modeling framework. We evaluate SCA on Twitter datasets in English, Hausa and Chinese. It achieves competetive coherence and diversity compared to BERTopic, while uncovering at least double the semantic components and maintaining a noise rate close to zero. Furthermore, SCA is scalable and effective across languages, including an underrepresented one.

You can find the preprint on [arXiv](https://arxiv.org/abs/2410.21054) and code on [GitHub](https://github.com/mainlp/semantic_components).