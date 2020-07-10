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
* Transformer with Hard-Coded Attention \[[pdf](https://www.aclweb.org/anthology/2020.acl-main.687.pdf)\] \[code](https://github.com/fallcat/stupidNMT)\]
  * Modified multi-headed attention to hard-coded Gaussian attention
  * Reduced memory and inference time speed without much BLEU drop
* RNN Machine Translation Faster Decoder
  * Generate a fixed span of words at a time to speed up decoder
  * Tried to add syntax to improve performance. Proved that it will slow down the model

* Key phrase extraction
  * Literature review in short text summarization and key phrase extraction
  * Used rule-based methods, statistics based methods, and deep learning models (CSDDM) in Python to successfully extract key phrases for customer QA data

Course Projects
======
* Scientific Paper Task, Problem and Contribution Identification and Tracking
  * Implemented candidates extraction by rules
  * Fine-tuned SciBERT on sentences that contain datasets to identify candidates that are true datasets

* Chinese to English Machine Translation Specialized in Game of Go and Cooking Recipe (Low-Resource Setting)
  * LSTM machine translation with Data augmentation by concatenating specialized terms in the dictionary
  * Improved BLEU metric for comparison in specialized fields
