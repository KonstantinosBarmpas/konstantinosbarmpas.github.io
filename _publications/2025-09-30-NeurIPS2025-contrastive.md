---
title: "Subject-Aware Contrastive Learning for EEG Foundation Models"
collection: publications
permalink: /publication/2025-09-30-NeurIPS2025-contrastive
excerpt: 'Antonis Karantonis\*, <strong>Konstantinos Barmpas\*</strong>, Yannis Panagakis, Dimitrios Adamos, Nikolaos Laskaris and Stefanos Zafeiriou - [[Paper](https://openreview.net/pdf?id=MdgBATPjEu)] [[Poster](https://www.barmpas.com/publication/2025-09-30-NeurIPS2025-contrastive)] '
status: 'Published'
venue: '<strong>NeurIPS 2025</strong> - Workshop on Learning from Time Series for Health' 
authors: 'Antonis Karantonis\*, <strong>Konstantinos Barmpas\*</strong>, Yannis Panagakis, Dimitrios Adamos, Nikolaos Laskaris and Stefanos Zafeiriou'
date: 2025-09-30
---

Authors: Antonis Karantonis\*, <strong>Konstantinos Barmpas\*</strong>, Yannis Panagakis, Dimitrios Adamos, Nikolaos Laskaris and Stefanos Zafeiriou

[[Workshop Page](https://timeseries4health.github.io)] - [[Conference Page](https://neurips.cc/)]

Foundation models are beginning to reshape EEG representation learning, but existing approaches remain dominated by self-supervised reconstruction objectives. In this work, we introduce the first subject-aware contrastive EEG foundation model, leveraging subject identity as a natural supervisory signal. Building on a patch-based architecture inspired by recent Large Brainwave Foundation Models (LBMs), we pretrain a lightweight transformer encoder using contrastive learning, where positive pairs are drawn from different segments and sessions of the same subject. Unlike contrastive foundation models in other domains, which depend on augmentations to construct positive samples, our method relies on naturally occurring intra-subject variability across EEG sessions. We evaluate the model through both representation metrics (alignment, uniformity and smooth effective rank) and downstream tasks (under linear probing and full fine-tuning). Results show that our model produces well-structured representation spaces, achieving strong representation quality and competitive performance compared to other LBMs.

**NeurIPS2025 Workshop on Learning from Time Series for Health Poster**

