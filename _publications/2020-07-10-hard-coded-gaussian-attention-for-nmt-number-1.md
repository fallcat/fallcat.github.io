---
title: "Hard-Coded Gaussian Attention for Neural Machine Translation"
collection: publications
permalink: /publication/2019-12-10-hard-coded-gaussian-attention-for-nmt-number-1
excerpt: 'This paper is about using hard-coded Gaussian Attention instead of learned Multi-headed Attention in Transformer in Neural Machine Translation.'
date: 2019-12-10
venue: 'Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics'
paperurl: 'https://www.aclweb.org/anthology/2020.acl-main.687.pdf'
citation: '@inproceedings{you-etal-2020-hard,
    title = "Hard-Coded {G}aussian Attention for Neural Machine Translation",
    author = "You, Weiqiu  and
      Sun, Simeng  and
      Iyyer, Mohit",
    booktitle = "Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics",
    month = jul,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.acl-main.687",
    pages = "7689--7700",
    abstract = "Recent work has questioned the importance of the Transformer{'}s multi-headed attention for achieving high translation quality. We push further in this direction by developing a hard-coded attention variant without any learned parameters. Surprisingly, replacing all learned self-attention heads in the encoder and decoder with fixed, input-agnostic Gaussian distributions minimally impacts BLEU scores across four different language pairs. However, additionally, hard-coding cross attention (which connects the decoder to the encoder) significantly lowers BLEU, suggesting that it is more important than self-attention. Much of this BLEU drop can be recovered by adding just a single learned cross attention head to an otherwise hard-coded Transformer. Taken as a whole, our results offer insight into which components of the Transformer are actually important, which we hope will guide future work into the development of simpler and more efficient attention-based models.",
}'

---
Recent work has questioned the importance of the Transformer’s multi-headed attention for achieving high translation quality. We push further in this direction by developing a “hard-coded” attention variant without any learned parameters. Surprisingly, replacing all learned self-attention heads in the encoder and decoder with fixed, input-agnostic Gaussian distributions minimally impacts BLEU scores across four different language pairs. However, additionally, hard-coding cross attention (which connects the decoder to the encoder) significantly lowers BLEU, suggesting that it is more important than self-attention. Much of this BLEU drop can be recovered by adding just a single learned cross attention head to an otherwise hard-coded Transformer. Taken as a whole, our results offer insight into which components of the Transformer are actually important, which we hope will guide future work into the development of simpler and more efficient attention-based models.

[pdf](https://www.aclweb.org/anthology/2020.acl-main.687.pdf)[code](https://github.com/fallcat/stupidNMT)
