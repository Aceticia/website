---
title: "VoxelFormer: Parameter-Efficient Multi-Subject Visual Decoding from fMRI" 
date: 2025-09-25
tags: ["fMRI", "Deep Learning", "Neuroscience"]
author: ["Chenqian Le", "Yilin Zhao", "Nikasadat Emami", "Kushagra Yadav", "Xujin Chris Liu", "Xupeng Chen", "Yao Wang"]
description: "VoxelFormer is a lightweight transformer architecture that enables multi-subject training for visual decoding from fMRI."
summary: "VoxelFormer is a lightweight transformer architecture that enables multi-subject training for visual decoding from fMRI."
cover:
    image: "voxel_former_thumbnail.png"
    alt: "VoxelFormer: Parameter-Efficient Multi-Subject Visual Decoding from fMRI"
    relative: true
editPost:
    URL: "https://cmsworkshops.com/NER2025/view_paper.php?PaperNum=1300"
    Text: "IEEE NER 2025 Spotlight poster"

---

##### Links
+ [Paper pdf](./ner_fmri.pdf)
+ [Code](https://github.com/kushagrayadv/voxel-former)

##### Abstract

Recent advances in fMRI-based visual decoding have enabled compelling reconstructions of perceived images. However, most approaches rely on subject-specific training, limiting scalability and practical deployment. VoxelFormer is a lightweight transformer architecture that enables multi-subject training for visual decoding from fMRI. VoxelFormer integrates a Token Merging Transformer (ToMer) for efficient voxel compression and a query-driven Q-Former that produces fixed-size neural representations aligned with the CLIP image embedding space.

##### My role in this project
I proposed the question formulation, architecture and guided the students through the project.

---

##### Citation

```latex
@ARTICLE{Le2025-vd,
  title         = "{VoxelFormer}: Parameter-efficient multi-subject visual
                   decoding from {fMRI}",
  author        = "Le, Chenqian and Zhao, Yilin and Emami, Nikasadat and Yadav,
                   Kushagra and Liu, Xujin ``chris and Chen, Xupeng and Wang,
                   Yao",
  journal       = "arXiv [cs.CV]",
  month         =  sep,
  year          =  2025,
  archivePrefix = "arXiv",
  primaryClass  = "cs.CV",
  eprint        = "2509.09015"
}
```
