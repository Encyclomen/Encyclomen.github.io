---
title: "Exploring Contextual Word-level Style Relevance for Unsupervised Style Transfer"
collection: publications
permalink: /publication/2020-05-08-Exploring-Contextual-Word-level-Style-Relevance-for-Unsupervised-Style-Transfer
excerpt: 'Unsupervised style transfer aims to change the style of an input sentence while preserving its original content without using parallel training data...'
date: 2020-05-08
venue: 'ACL'
paperurl: 'https://arxiv.org/pdf/2005.02049.pdf'
---
Unsupervised style transfer aims to change the style of an input sentence while preserving its original content without using parallel training data. In current dominant approaches, owing to the lack of fine-grained control on the influence from the target style,they are unable to yield desirable output sentences. In this paper, we propose a novel attentional sequence-to-sequence (Seq2seq) model that dynamically exploits the relevance of each output word to the target style for unsupervised style transfer. Specifically, we first pretrain a style classifier, where the relevance of each input word to the original style can be quantified via layer-wise relevance propagation. In a denoising auto-encoding manner, we train an attentional Seq2seq model to reconstruct input sentences and repredict word-level previously-quantified style relevance simultaneously. In this way, this model is endowed with the ability to automatically predict the style relevance of each output word. Then, we equip the decoder of this model with a neural style component to exploit the predicted wordlevel style relevance for better style transfer. Particularly, we fine-tune this model using a carefully-designed objective function involving style transfer, style relevance consistency, content preservation and fluency modeling loss terms. Experimental results show that our proposed model achieves state-of-the-art performance in terms of both transfer accuracy and content preservation.

[Download paper here](https://arxiv.org/pdf/2005.02049.pdf)
