---
title: "Confidence Based Bidirectional Global Context Aware Training Framework for Neural Machine Translation"
collection: publications
permalink: /publication/2022-02-23-Confidence-Based-Bidirectional-Global-Context-Aware-Training-Framework-for-Neural-Machine-Translation
excerpt: 'Most dominant neural machine translation (NMT) models are restricted to make predictions only according to the local context of preceding words in a left-to-right manner...'
date: 2022-02-23
venue: 'ACL'
paperurl: 'https://aclanthology.org/2022.acl-long.206.pdf'
---
Most dominant neural machine translation (NMT) models are restricted to make predictions only according to the local context of preceding words in a left-to-right manner. Although many previous studies try to incorporate global information into NMT models, there still exist limitations on how to effectively exploit bidirectional global context. In this paper, we propose a Confidence Based Bidirectional Global Context Aware (CBBGCA) training framework for NMT, where the NMT model is jointly trained with an auxiliary conditional masked language model (CMLM). The training consists of two stages: (1) multi-task joint training; (2) confidence based knowledge distillation. At the first stage, by sharing encoder parameters, the NMT model is additionally supervised by the signal from the CMLM decoder that contains bidirectional global contexts. Moreover, at the second stage, using the CMLM as teacher, we further pertinently incorporate bidirectional global context to the NMT model on its unconfidently-predicted target words via knowledge distillation. Experimental results show that our proposed CBBGCA training framework significantly improves the NMT model by +1.02, +1.30 and +0.57 BLEU scores on three large-scale translation datasets, namely WMT'14 English-to-German, WMT'19 Chinese-to-English and WMT'14 English-to-French, respectively.

[Download paper here](https://aclanthology.org/2022.acl-long.206.pdf)
