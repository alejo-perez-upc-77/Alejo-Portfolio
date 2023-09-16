---
date: 2022-01-20T11:00:59-04:00
description: "Project on NLP, Bot Recognition in Twitter"
featured_image: "/images/twitter.jpg"
tags: ["NLP", "Text Mining", "Bot Recognition"]
title: "Empirical Study for bot recognition Using Bert and BiLSTMs"
---

# Abstract

Pre-trained language models together with the finetuning practices have been experiencing a remarkable improvement at NLP tasks during the last years. These models are learnt from well-written text corpora that share characteristics of academical and literary grammar, syntax, and lexicon. Literary works, Wikipedia and News are a few examples of these. When it comes to Tweet Spambot Recognition, we must deal with a big drawback: the difficulty of leveraging the prior knowledge of language models when applied on data that belong to an especially different domain. Social media text, such as Twitter tweets, features many peculiarities (own memes, emojis, hashtags, “at” symbols, misspellings, grammar incorrectness, etc.).

{{< figure src="/images/bilstm_flow.png" >}}

In order to explore how these language models generalize on these web data distributions, we explored some Deep Learning language model architectures to research how they perform at the tweet Spambot Classification task. We used a fine-tuning approach to test the classification performance of BERT, Bi-LSTMs, and other classic Machine Learning techniques at several tweet data datasets. Our results show several experiments that yielded satisfactory performance. Hence, further research is needed to exploit the text-level classification against the traditional meta-data techniques that spend a lot of time and computational resources.

* [Link](https://github.com/alejo-perez-upc-77/BERT-Bi-LSTM-Bot-Recognition) to GitHub Repository
* [Link](https://github.com/alejo-perez-upc-77/BERT-Bi-LSTM-Bot-Recognition/blob/master/TM_Report_alepe026.pdf) to GitHub Article