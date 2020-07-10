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
* Transformer with Hard-Coded Attention
  * Modified multi-headed attention to hard-coded Gaussian attention
  * Reduced memory and inference time speed without much BLEU drop
* RNN Machine Translation Faster Decoder \[[pdf](/assets/pdf/rnn_faster_decoder.pdf)\] \[[code](https://github.com/fallcat/rnn_nmt_syntax)\]
  * Generate a fixed span of words at a time to speed up decoder
  * Tried to add syntax to improve performance. Proved that it will slow down the model

* Key phrase extraction
  * Literature review in short text summarization and key phrase extraction
  * Used rule-based methods, statistics based methods, and deep learning models (CSDDM) in Python to successfully extract key phrases for customer QA data

Course Projects
======
* Scientific Paper Task, Problem and Contribution Identification and Tracking \[[pdf](/assets/pdf/sci_paper_kb.pdf)\] \[[code](https://github.com/fallcat/sci-paper-kb)\]
  * Implemented candidates extraction by rules
  * Fine-tuned SciBERT on sentences that contain datasets to identify candidates that are true datasets

* Chinese to English Machine Translation Specialized in Game of Go and Cooking Recipe (Low-Resource Setting) \[[pdf](/assets/pdf/go_nmt.pdf)\]
  * LSTM machine translation with Data augmentation by concatenating specialized terms in the dictionary
  * Improved BLEU metric for comparison in specialized fields
