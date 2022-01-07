---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---

{% include base_path %}

Research Projects
======
* Zero-shot image classification with text descriptions
  * Improve on using BART as text embedding with pretraining objectives
* Amazon Alexa Prize Taskbot

* Comparing supervised and unsupervised neural machine translation with macro averaging
  * Even if a supervised NMT model and an unsupervised NMT model have the same BLEU, the SNMT model often translates with fewer untranslated words and less truncations. 

* Transformer with Hard-Coded Attention \[[pdf](https://www.aclweb.org/anthology/2020.acl-main.687.pdf)\] \[[code](https://github.com/fallcat/stupidNMT)\]
  * Modified multi-headed attention to hard-coded Gaussian attention
  * Reduced memory and inference time speed without much BLEU drop
* RNN Machine Translation Faster Decoder
  * Generate a fixed span of words at a time to speed up decoder
  * Tried to add syntax to improve performance. Proved that it will slow down the model

* Key phrase extraction
  * Literature review in short text summarization and key phrase extraction
  * Used rule-based methods, statistics based methods, and deep learning models (CSDDM) in Python to successfully extract key phrases for customer QA data
