---
title: "EEG-D3: A Solution to the Hidden Overfitting Problem of Deep Learning Models"
collection: publications
permalink: /publication/2025-12-15-phase-classification
excerpt: 'Siegfried Ludwig, Stylianos Bakas, <strong>Konstantinos Barmpas</strong>, Georgios Zoumpourlis, Dimitrios Adamos, Nikolaos Laskaris, Yannis Panagakis and Stefanos Zafeiriou'
status: 'Published'
venue: '<strong>Preprint</strong>' 
authors: 'Siegfried Ludwig, Stylianos Bakas, <strong>Konstantinos Barmpas</strong>, Georgios Zoumpourlis, Dimitrios Adamos, Nikolaos Laskaris, Yannis Panagakis and Stefanos Zafeiriou'
date: 2025-12-15
---

Authors: Siegfried Ludwig, Stylianos Bakas, <strong>Konstantinos Barmpas</strong>, Georgios Zoumpourlis, Dimitrios Adamos, Nikolaos Laskaris, Yannis Panagakis and Stefanos Zafeiriou

Deep learning for decoding EEG signals has gained traction, with many claims to state-of-the-art accuracy. However, despite the convincing benchmark performance, successful translation to real applications is limited. The frequent disconnect between performance on controlled BCI benchmarks and its lack of generalisation to practical settings indicates hidden overfitting problems. We introduce Disentangled Decoding Decomposition (D3), a weakly supervised method for training deep learning models across EEG datasets. By predicting the place in the respective trial sequence from which the input window was sampled, EEG-D3 separates latent components of brain activity, akin to non-linear ICA. We utilise a novel model architecture with fully independent sub-networks for strict interpretability. We outline a feature interpretation paradigm to contrast the component activation profiles on different datasets and inspect the associated temporal and spatial filters. The proposed method reliably separates latent components of brain activity on motor imagery data. Training downstream classifiers on an appropriate subset of these components prevents hidden overfitting caused by task-correlated artefacts, which severely affects end-to-end classifiers. We further exploit the linearly separable latent space for effective few-shot learning on sleep stage classification. The ability to distinguish genuine components of brain activity from spurious features results in models that avoid the hidden overfitting problem and generalise well to real-world applications, while requiring only minimal labelled data. With interest to the neuroscience community, the proposed method gives researchers a tool to separate individual brain processes and potentially even uncover heretofore unknown dynamics.
