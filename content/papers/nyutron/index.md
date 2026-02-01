---
title: "Health system-scale language models are all-purpose prediction engines" 
date: 2023-10-18
tags: ["Clinical NLP", "Language Models", "Medical AI"]
author: ["Lavender Yao Jiang", "Xujin Chris Liu", "...", "Eric Karl Oermann"]
description: "We trained a large language model for medical language (NYUTron) and subsequently fine-tuned it across a wide range of clinical and operational predictive tasks, and found that it outperforms traditional models while being much easier to deploy."
summary: "We trained a large language model for medical language (NYUTron) and subsequently fine-tuned it across a wide range of clinical and operational predictive tasks, and found that it outperforms traditional models while being much easier to deploy."
cover:
    image: "nyutron.webp"
    alt: "Health system-scale language models are all-purpose prediction engines"
    relative: true
editPost:
    URL: "https://www.nature.com/articles/s41586-023-06160-y"
    Text: "Nature"

---

##### Links
+ [Paper](https://www.nature.com/articles/s41586-023-06160-y)
+ [Code](https://github.com/nyuolab/NYUTron)

##### Abstract

Physicians make critical time-constrained decisions every day. Clinical predictive models can help physicians and administrators make decisions by forecasting clinical and operational events. Existing structured data-based clinical predictive models have limited use in everyday practice owing to complexity in data processing, as well as model development and deployment. Here we show that unstructured clinical notes from the electronic health record can enable the training of clinical language models, which can be used as all-purpose clinical predictive engines with low-resistance development and deployment. Our approach leverages recent advances in natural language processing to train a large language model for medical language (NYUTron) and subsequently fine-tune it across a wide range of clinical and operational predictive tasks. We evaluated our approach within our health system for five such tasks: 30-day all-cause readmission prediction, in-hospital mortality prediction, comorbidity index prediction, length of stay prediction, and insurance denial prediction. We show that NYUTron has an area under the curve (AUC) of 78.7–94.9%, with an improvement of 5.36–14.7% in the AUC compared with traditional models. We additionally demonstrate the benefits of pretraining with clinical text, the potential for increasing generalizability to different sites through fine-tuning and the full deployment of our system in a prospective, single-arm trial. These results show the potential for using clinical language models in medicine to read alongside physicians and provide guidance at the point of care.

##### My role in this project
I helped with debugging and improving the training and evaluation infrastructure.

---

##### Citation

```latex
@ARTICLE{Jiang2023-io,
  title    = "Health system-scale language models are all-purpose prediction
              engines",
  author   = "Jiang, Lavender Yao and Liu, Xujin Chris and Nejatian, Nima Pour
              and Nasir-Moin, Mustafa and Wang, Duo and Abidin, Anas and Eaton,
              Kevin and Riina, Howard Antony and Laufer, Ilya and Punjabi,
              Paawan and Miceli, Madeline and Kim, Nora C and Orillac, Cordelia
              and Schnurman, Zane and Livia, Christopher and Weiss, Hannah and
              Kurland, David and Neifert, Sean and Dastagirzada, Yosef and
              Kondziolka, Douglas and Cheung, Alexander T M and Yang, Grace and
              Cao, Ming and Flores, Mona and Costa, Anthony B and
              Aphinyanaphongs, Yindalon and Cho, Kyunghyun and Oermann, Eric
              Karl",
  journal  = "Nature",
  month    =  jun,
  year     =  2023,
  doi      = "10.1038/s41586-023-06160-y",
  pmc      =  6821018,
  pmid     =  37286606,
  issn     = "0028-0836,1476-4687",
  language = "en"
}

```