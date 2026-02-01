---
title: "Longitudinal deep neural networks for
assessing metastatic brain cancer on a large open benchmarks" 
date: 2024-09-06
tags: ["Medical Imaging", "Deep Learning", "Machine Learning", "Computer Vision"]
author: ["Katherine E. Link", "Zane Schnurman", "Xujin Chris Liu", "Young Joon Fred Kwon", "Lavender Yao Jiang", "Mustafa Nasir-Moin", "Sean Neifert", "Juan Diego Alzate", "Kenneth Bernstein", "Tanxia Qu", "Viola Chen", "Eunice Yang", "John G. Golfinos", "Daniel Orringer", "Douglas Kondziolka", "Eric Karl Oermann"]
description: "We present NYUMets-Brain, the world’s largest, longitudinal, real-world dataset of cancer consisting of the imaging, clinical follow-up, and medical management of 1,429 patients. Using this dataset we developed Segmentation-Through-Time, a deep neural network which explicitly utilizes the longitudinal structure of the data and obtained state-of-the-art results at small (<10 mm3) metastases detection and segmentation." 
summary: "We present NYUMets-Brain, the world’s largest, longitudinal, real-world dataset of cancer consisting of the imaging, clinical follow-up, and medical management of 1,429 patients. Using this dataset we developed Segmentation-Through-Time, a deep neural network which explicitly utilizes the longitudinal structure of the data and obtained state-of-the-art results at small (<10 mm3) metastases detection and segmentation." 
cover:
    image: "nyumets_thumbnail.png"
    alt: "Longitudinal deep neural networks for assessing metastatic brain cancer on a large open benchmarks"
    relative: true
editPost:
    URL: "https://www.nature.com/articles/s41467-024-52414-2"
    Text: "Nature Communications"

---

##### Links
+ [Paper](https://www.nature.com/articles/s41467-024-52414-2)
+ [Code](https://github.com/nyumets/nyumets.git)
+ [Website](https://nyumets.org/)

##### Abstract

The detection and tracking of metastatic cancer over the lifetime of a patient remains a major challenge in clinical trials and real-world care. Advances in deep learning combined with massive datasets may enable the development of tools that can address this challenge. We present NYUMets-Brain, the world’s largest, longitudinal, real-world dataset of cancer consisting of the imaging, clinical follow-up, and medical management of 1,429 patients. Using this dataset we developed Segmentation-Through-Time, a deep neural network which explicitly utilizes the longitudinal structure of the data and obtained state-of-the-art results at small (<10 $mm^3$) metastases detection and segmentation. We also demonstrate that the monthly rate of change of brain metastases over time are strongly predictive of overall survival (HR 1.27, 95%CI 1.18-1.38). We are releasing the dataset, codebase, and model weights for other cancer researchers to build upon these results and to serve as a public benchmark.

##### My role in this project
I'm responsible for building the self-supervised learning framework to pretrain the segmentation models, and the longitudinal modeling framework to leverage the longitudinal structure of the data. I also wrote the rigorous hyperparameter serach, ablation studies, and benchmarking to demonstrate the effectiveness of the proposed methods.

---

##### Citation

```latex
@ARTICLE{Link2024-tq,
  title     = "Longitudinal deep neural networks for assessing metastatic brain
               cancer on a large open benchmark",
  author    = "Link, Katherine E and Schnurman, Zane and Liu, Chris and Kwon,
               Young Joon Fred and Jiang, Lavender Yao and Nasir-Moin, Mustafa
               and Neifert, Sean and Alzate, Juan Diego and Bernstein, Kenneth
               and Qu, Tanxia and Chen, Viola and Yang, Eunice and Golfinos,
               John G and Orringer, Daniel and Kondziolka, Douglas and Oermann,
               Eric Karl",
  journal   = "Nat. Commun.",
  publisher = "Springer Science and Business Media LLC",
  volume    =  15,
  number    =  1,
  pages     =  8170,
  month     =  sep,
  year      =  2024,
  doi       = "10.1038/s41467-024-52414-2",
  pmc       = "PMC11408643",
  pmid      =  39289405,
  issn      = "2041-1723,2041-1723",
  language  = "en"
}
```