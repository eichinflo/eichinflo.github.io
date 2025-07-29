---
title: "What's the Difference? Supporting Users in Identifying the Effects of Prompt and Model Changes Through Token Patterns"
collection: publications
permalink: /publication/2025-04-22-whats-the-difference
excerpt: 'We propose a method for evaluating the influence of prompts on the LLM outputs through token patterns.'
date: 2025-04-22
venue: 'ACL 2025 Main'
paperurl: 'https://aclanthology.org/2025.acl-long.985/'
authors: 'Michael A. Hedderich, Anyi Wang, Raoyuan Zhao, <b>Florian Eichin</b>, and Barbara Plank'
---

Prompt engineering for large language models is challenging, as even small prompt perturbations or model changes can significantly impact the generated output texts. Existing evaluation methods, either automated metrics or human evaluation, have limitations, such as providing limited insights or being labor-intensive. We propose Spotlight, a new approach that combines both automation and human analysis. Based on data mining techniques, we automatically distinguish between random (decoding) variations and systematic differences in language model outputs. This process provides token patterns that describe the systematic differences and guide the user in manually analyzing the effects of their prompt and model changes efficiently. We create three benchmarks to quantitatively test the reliability of token pattern extraction methods and demonstrate that our approach provides new insights into established prompt data. From a human-centric perspective, through demonstration studies and a user study, we show that our token pattern approach helps users understand the systematic differences of language model outputs, and we are able to discover relevant differences caused by prompt and model changes (e.g. related to gender or culture), thus supporting the prompt engineering process and human-centric model behavior research.

You can find the paper on [arXiv](https://arxiv.org/abs/2504.15815) and [ACL Anthology](https://aclanthology.org/2025.acl-long.985/). An implementation of SPOTlight is maintained on [GitHub](https://github.com/mainlp/spotlight).