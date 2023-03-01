---
title: "A Multi-Task Multi-Stage Transitional Training Framework for Neural Chat Translation."
collection: publications
permalink: /publication/2022-12-30-A-Multitask-Multistage-Transitional-Training-Framework-for-Neural-Chat-Translation
excerpt: 'Neural chat translation (NCT) aims to translate a cross-lingual chat between speakers of different languages. Existing context-aware NMT models cannot...'
date: 2022-12-30
venue: 'TPAMI'
link: 'https://arxiv.org/pdf/2301.11749.pdf'
---
Neural chat translation (NCT) aims to translate a cross-lingual chat between speakers of different languages. Existing context-aware NMT models cannot achieve satisfactory performances due to the following inherent problems: 1) limited resources of annotated bilingual dialogues; 2) the neglect of modelling conversational properties; 3) training discrepancy between different stages. To address these issues, in this paper, we propose a m ulti-task m ulti-stage t ransitional (MMT) training framework, where an NCT model is trained using the bilingual chat translation dataset and additional monolingual dialogues. We elaborately design two auxiliary tasks, namely utterance discrimination and speaker discrimination, to introduce the modelling of dialogue coherence and speaker characteristic into the NCT model. The training process consists of three stages: 1) sentence-level pre-training on large-scale parallel corpus; 2) intermediate training with auxiliary tasks using additional monolingual dialogues; 3) context-aware fine-tuning with gradual transition. Particularly, the second stage serves as an intermediate phase that alleviates the training discrepancy between the pre-training and fine-tuning stages. Moreover, to make the stage transition smoother, we train the NCT model using a gradual transition strategy, i.e. , gradually transiting from using monolingual to bilingual dialogues. Extensive experiments on two language pairs demonstrate the effectiveness and superiority of our proposed training framework.

[Download paper here](https://arxiv.org/pdf/2301.11749.pdf)
