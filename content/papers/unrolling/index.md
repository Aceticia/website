---
title: "Lightweight Transformer for EEG Classification via Balanced Signed Graph Algorithm Unrolling
" 
date: 2026-01-26
tags: ["Machine Learning", "EEG", "Graph Neural Networks"]
author: ["Junyi Yao", "Parham Eftekhar", "Gene Cheung", "Xujin Chris Liu", "Yao Wang", "Wei Hu"]
description: "We build lightweight and interpretable transformer-like neural nets by unrolling a spectral denoising algorithm for signals on a balanced signed graph---graph with no cycles of odd number of negative edges. Experiments show that our method achieves classification performance comparable to representative deep learning schemes, while employing dramatically fewer parameters."
summary: "We build lightweight and interpretable transformer-like neural nets by unrolling a spectral denoising algorithm for signals on a balanced signed graph---graph with no cycles of odd number of negative edges. Experiments show that our method achieves classification performance comparable to representative deep learning schemes, while employing dramatically fewer parameters." 
cover:
    image: "thumbnail.png"
    alt: "Lightweight Transformer for EEG Classification via Balanced Signed Graph Algorithm Unrolling"
    relative: true
editPost:
    URL: "https://openreview.net/forum?id=zxsLio384j"
    Text: "OpenReview"

---

##### Links
+ [OpenReview](https://openreview.net/forum?id=zxsLio384j)

##### Abstract

Samples of brain signals collected by EEG sensors have inherent anti-correlations that are well modeled by negative edges in a finite graph. To differentiate epilepsy patients from healthy subjects using collected EEG signals, we build lightweight and interpretable transformer-like neural nets by unrolling a spectral denoising algorithm for signals on a balanced signed graph---graph with no cycles of odd number of negative edges. A balanced signed graph has well-defined frequencies that map to a corresponding positive graph via similarity transform of the graph Laplacian matrices. We implement an ideal low-pass filter efficiently on the mapped positive graph via Lanczos approximation, where the optimal cutoff frequency is learned from data. Given that two balanced signed graph denoisers learn posterior probabilities of two different signal classes during training, we evaluate their reconstruction errors for binary classification of EEG signals. Experiments show that our method achieves classification performance comparable to representative deep learning schemes, while employing dramatically fewer parameters.

##### My role in the project

I advised on the evaluation paradigm, dataset choices, and result interpretation.

---

##### Citation

```latex
@INPROCEEDINGS{Yao2025-tv,
  title     = "Lightweight Transformer for {EEG} Classification via Balanced
               Signed Graph Algorithm Unrolling",
  author    = "Yao, Junyi and Eftekhar, Parham and Cheung, Gene and Liu, Xujin
               Chris and Wang, Yao and Hu, Wei",
  booktitle = "The Fourteenth International Conference on Learning
               Representations",
  month     =  oct,
  year      =  2025
}
```
