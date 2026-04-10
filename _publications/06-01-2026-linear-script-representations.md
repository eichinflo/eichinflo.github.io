---
title: "Linear Script Representations in Speech Foundation Models Enable Zero-Shot Transliteration"
collection: publications
permalink: /publication/06-01-2026-linear-script-representations
excerpt: 'We show that script is largely represented as a single linear direction in activation space of Whisper models and that steering activations towards that direction enables transcriptions and even generalizes across different languages.'
date: 2026-01-06
venue: 'ACL 2026 Findings'
paperurl: 'https://arxiv.org/pdf/2601.02906'
authors: 'Ryan Soh-Eun Shim, Kwanghee Choi, Kalvin Chang, Ming-Hao Hsu, <b>Florian Eichin</b>, Zhizheng Wu, Alane Suhr, Michael A. Hedderich, David Harwath, David R. Mortensen, Barbara Plank'
---

Multilingual speech foundation models such as Whisper are trained on web-scale data, where data for each language consists of a myriad of regional varieties. However, different regional varieties often employ different scripts to write the same language, rendering speech recognition output also subject to non-determinism in the output script. To mitigate this problem, we show that script is linearly encoded in the activation space of multilingual speech models, and that modifying activations at inference time enables direct control over output script. We find the addition of such script vectors to activations at test time can induce script change even in unconventional language-script pairings (e.g. Italian in Cyrillic and Japanese in Latin script). We apply this approach to inducing post-hoc control over the script of speech recognition output, where we observe competitive performance across all model sizes of Whisper.

Preprint is live on [arXiv](https://arxiv.org/pdf/2601.02906)!

More information on [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7417141674453254144/) and [BlueSky](https://bsky.app/profile/did:plc:t5dcavtecrqq6ilc5qyl6366/post/3mbsiakrby22m).