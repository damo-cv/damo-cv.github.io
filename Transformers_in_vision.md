---
layout: default
---

# Transformers in Computer Vision


## **1. How to build a better transformer model**


### _Scaled ReLU Matters for Training Vision Transformers.[AAAI'22]_ [pdf](https://arxiv.org/abs/2109.03810) 

We verify, both theoretically and empirically, that scaled ReLU in \textit{conv-stem} not only improves training stabilization, but also increases the diversity of patch tokens, thus boosting peak performance with a large margin via adding few parameters and flops.


### _kVT: k-NN Attention for Boosting Vision Transformers._ [pdf](https://arxiv.org/abs/2106.00515) 

We propose a sparse attention scheme, dubbed k-NN attention, for boosting vision transformers. Specifically, instead of involving all the tokens for attention matrix calculation, we only select the top-k similar tokens from the keys for each query to compute the attention map. The proposed k-NN attention naturally inherits the local bias of CNNs without introducing convolutional operations. It allows for the exploration of long range correlation and at the same time filter out irrelevant tokens by choosing the most similar tokens from the entire image. Theoretically analysis shows that k-NN attention is powerful in distilling noise from input tokens and in speeding up training.


### _ELSA: Enhanced Local Self-Attention for Vision Transformer._ [paper](https://arxiv.org/abs/2112.12786) [code](https://github.com/damo-cv/ELSA)

Self-attention is powerful in modeling long-range dependencies, but it is weak in local finer-level feature learning. We comprehensively investigate local self-attention and its counterparts from two sides: channel setting and spatial processing. We propose the enhanced local self-attention (ELSA) with Hadamard attention and the ghost head, to boost any transformer-based models without architecture / hyperparameter modification.


## **2. Applying Transformers to Vision Applications**


### _TransReID: Transformer-based Object Re-Identification.[ICCV'21]_ [pdf](https://openaccess.thecvf.com/content/ICCV2021/papers/He_TransReID_Transformer-Based_Object_Re-Identification_ICCV_2021_paper.pdf), [code](https://github.com/damo-cv/TransReID), [presentation (in Chinese)](https://damo.alibaba.com/download/?id=tY2x8irYoEXM5Q)

*   The **first** pure Transformer-based ReID method;
*   State-of-the-art performance on 6 ReID benchmarks, including person ReID, vehicle ReID, and occluded ReID.


### _CDTrans: Cross-domain Transformer for Unsupervised Domain Adaptation._ [pdf](https://arxiv.org/abs/2109.06165) [code]()

*   The first work to apply cross-domain Transformers for unsupervised domain adaptation;
*   State-of-the-art performance on several domain adaptation benchmarks.


### _Transformers in "2021 AI City Challenge"._

*   1st place in Track 2: City-Scale Multi-Camera Vehicle Re-Identification. [report](https://github.com/LCFractal/AIC21-MTMC) [code](https://github.com/michuanhaohao/AICITY2021_Track2_DMT)
*   1st place in Track 3: City-Scale Multi-Camera Vehicle Tracking. [report](https://openaccess.thecvf.com/content/CVPR2021W/AICity/papers/Liu_City-Scale_Multi-Camera_Vehicle_Tracking_Guided_by_Crossroad_Zones_CVPRW_2021_paper.pdf) [code](https://github.com/michuanhaohao/AICITY2021_Track2_DMT)

Effective Vehicle ReID has been achieved by ensembling multiple models of CNNs and Transformers. 


[back](./)
