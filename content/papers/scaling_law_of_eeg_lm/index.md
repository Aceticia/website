---
title: "Dissecting EEG-Language Models: Token Granularity, Model Size, and Cross-Site Generalization" 
date: 2026-01-28
tags: ["EEG", "Language Models", "Medical AI"]
author: ["Xujin Chris Liu", "Yao Wang", "Eric Karl Oermann"]
description: "We investigate how token granularity and model size affect EEG-language model performance in both in-distribution and cross-site scenarios, and find that token granularity is a critical, task-dependent scaling dimension for clinical EEG models, sometimes more important than model size."
summary: "We investigate how token granularity and model size affect EEG-language model performance in both in-distribution and cross-site scenarios, and find that token granularity is a critical, task-dependent scaling dimension for clinical EEG models, sometimes more important than model size."
cover:
    image: "thumbnail.png"
    alt: "Dissecting EEG-Language Models: Token Granularity, Model Size, and Cross-Site Generalization"
    relative: true
# editPost:
#     URL: "https://www.nature.com/articles/s41586-023-06160-y"
#     Text: "Nature"

---

##### Links
+ [Paper](./paper.pdf)
+ [Code (Coming Soon)]()

##### Abstract

We investigate how token granularity and model size affect EEG-language model performance in both in-distribution and cross-site scenarios. We pretrain a 1D ConvNeXt tokenizer (Weaver tokenizer) and use it to adapt Qwen3 language models (Weaver model) with continual pretraining on the Big EEG (BEEG) dataset, the largest corpus of EEG, iEEG, and MEG data to date. Finetuning and evaluating on seizure detection and forecasting, we find that optimal scaling depends heavily on the task and whether evaluation is in-distribution. For seizure detection, finer tokenization consistently improves performance. On CHB-MIT and Siena, our models achieve balanced accuracy comparable to or exceeding state-of-the-art EEG foundation models. In contrast, cross-site seizure forecasting benefits significantly from coarser tokenization, challenging the assumption that higher fidelity is always better. While increasing language model size improves in-distribution detection, it offers no benefit for cross-site generalization. These results establish token granularity as a critical, task-dependent scaling dimension for clinical EEG models.

##### My role in this project
I proposed the project and fomulated the problem. I implemented the models, training, and evaluation pipeline.

---

##### Citation

(Under Review at ICML 2026)
