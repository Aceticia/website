---
title: "Automated, Scalable and Generalizable Deep Learning for Tracking Cortical Spreading Depression Using EEG" 
date: 2021-05-04
tags: ["EEG", "Deep Learning", "Medical AI"]
author: ["Xujin Liu", "Alireza Chamanzar", "Lavender Y. Jiang", "Kimon A. Vogt", "Jose M. F. Moura", "Pulkit Grover"]
description: "We present a graph neural network that is able to track cortical spreading depressions in scalp EEG signals. We show that our model is scalable to different densities of EEG and generalizable to different head models."
summary: "We present a graph neural network that is able to track cortical spreading depressions in scalp EEG signals. We show that our model is scalable to different densities of EEG and generalizable to different head models."
cover:
    image: "thumbnail.png"
    alt: "Automated, Scalable and Generalizable Deep Learning for Tracking Cortical Spreading Depression Using EEG"
    relative: true
editPost:
    URL: "https://ieeexplore.ieee.org/document/9441333"
    Text: "IEEE"

---

##### Links
+ [Paper link](https://ieeexplore.ieee.org/document/9441333)
+ [Paper pdf](csd_sparc.pdf)

##### Abstract

We present a non-invasive deep learning approach for tracking cortical spreading depressions (CSDs) in scalp electroencephalography (EEG) signals. Our method, which we refer to as CSD spatially aware convolutional network or CSD-SpArC, combines a convolutional neural network, which extracts temporal features from the EEG signal of each electrode, with a graph neural network, which exploits the spatial structure of EEG signals on the scalp. Using high-density EEG, this combination of networks misses no CSDs, even the narrowest ones (informed by widths observed in the real world), with less than 1.3% “post-stitching” false alarm rate. We further use the network to track CSD wave propagation by detecting when the recording at each electrode is affected substantially by the propagating wave, quantifying its “spatio-temporal tracking accuracy.” Tested on simulated CSD waves on real head MRI models of 4 subjects, CSD-SpArC achieves spatio-temporal tracking accuracies of up to 86.65%±0.60%, with an average false alarm rate less than 3.5%, using high-density EEG (256 electrodes). We show the scalability of our trained network to different densities of EEG and generalizability to different head models.

##### My role in the project
I designed and implemented the graph neural network model, training, and evaluation code.

---

##### Citation

```latex
@INPROCEEDINGS{9441333,
  author={Chamanzar, Alireza and Liu, Xujin and Jiang, Lavender Y. and Vogt, Kimon A. and Moura, José M. F. and Grover, Pulkit},
  booktitle={2021 10th International IEEE/EMBS Conference on Neural Engineering (NER)}, 
  title={Automated, Scalable and Generalizable Deep Learning for Tracking Cortical Spreading Depression Using EEG}, 
  year={2021},
  volume={},
  number={},
  pages={416-419},
  keywords={Electrodes;Deep learning;Scalability;Propagation;Scalp;Neural engineering;Feature extraction},
  doi={10.1109/NER49283.2021.9441333}}
```
