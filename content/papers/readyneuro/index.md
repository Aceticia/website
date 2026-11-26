---
title: "Scaling fMRI Foundation Models with Native-Space Data from Heterogeneous Public Studies"
date: 2026-11-25
tags: ["fMRI", "Foundation Models", "Neuroscience", "Deep Learning"]
author: ["Xujin Chris Liu", "Connor Lane", "Hassan Muhammad", "Tanishq Abraham", "Paul Scotti"]
description: "We skip nonlinear template warping, preprocess most of OpenNeuro's eligible fMRI into the 22,373-hour ReadyNeuro corpus, and pretrain CortexMAE-ReadyNeuro on it. Native-space pretraining performs roughly on par with template-space pretraining."
summary: "We skip nonlinear template warping, preprocess most of OpenNeuro's eligible fMRI into the 22,373-hour ReadyNeuro corpus, and pretrain CortexMAE-ReadyNeuro on it. Native-space pretraining performs roughly on par with template-space pretraining."
cover:
    image: "readyneuro_thumbnail.png"
    alt: "Scaling fMRI Foundation Models with Native-Space Data from Heterogeneous Public Studies"
    relative: true
editPost:
    URL: "https://openreview.net/forum?id=rLMKAJCLc1"
    Text: "NeurIPS 2026 Workshop on Foundation Models for the Brain and Body"

---

##### Links
+ [Paper](https://openreview.net/forum?id=rLMKAJCLc1)
+ [Blog post](https://sophont.med/blog/native-fmri/)
+ [Code](https://github.com/SophontAI/CortexMAE-ReadyNeuro)
+ [Data](https://github.com/SophontAI/ReadyNeuro)
+ [Weights](https://huggingface.co/medarc/CortexMAE-ReadyNeuro)

##### Abstract

Preparing fMRI for foundation model training usually involves computationally expensive data cleaning and alignment steps, including nonlinear deformation of brains to a shared anatomical template. We test a minimalist approach that preserves brains' native shape and greatly simplifies the preprocessing pipeline, placing more burden on the foundation model. Our pipeline prepares the median participant's data in less than 16 minutes on one CPU core, enabling us to train the full-corpus CortexMAE-ReadyNeuro model, the first fMRI foundation model pretrained on most of OpenNeuro's eligible data, on ReadyNeuro: 22,373 recording hours from 837 studies and approximately 30,000 participants. We evaluate the resulting model on seven classification tasks from the Brainmarks benchmark suite. We hypothesized that native-space pretraining would trail template-space pretraining at matched data scale and that scaling to more data would close the gap. Surprisingly, the two perform roughly on par, and at a fixed training budget, more data gives modest gains. Our work is an initial step toward large-scale native-space pretraining. We release our code, the ReadyNeuro training-ready shards, and the pretrained weights.

##### My role in the project
I led the project during my summer 2026 internship at Sophont: I built the native-space preprocessing pipeline, assembled the ReadyNeuro corpus from OpenNeuro, adapted CortexMAE to native-space data, and ran the pretraining, scaling and evaluation experiments.

---

##### Citation
```latex
@inproceedings{liu2026scaling,
  title     = {Scaling {fMRI} Foundation Models with Native-Space Data from Heterogeneous Public Studies},
  author    = {Liu, Xujin Chris and Lane, Connor and Muhammad, Hassan and Abraham, Tanishq Mathew and Scotti, Paul Steven},
  booktitle = {NeurIPS 2026 Workshop on Foundation Models for the Brain and Body},
  year      = {2026},
  url       = {https://openreview.net/forum?id=rLMKAJCLc1}
}
```
