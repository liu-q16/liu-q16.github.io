---
title: "Cancer Drug Response Prediction via a Hybrid Graph Convolutional Network"
collection: publications
permalink: /publications/DeepCDR
date: 2019-7-20
citation: '<b>Qiao Liu</b>, Zhiqiang Hu, Rui Jiang and Mu Zhou <i>The 28th conference on Intelligent Systems for Molecular Biology</i>. <b>ISMB 2020</b>.'
---
[[Paper](http://liu-q16.github.io/files/DeepCDR.pdf)] [[Code](https://github.com/kimmo1019/DeepCDR)]


## Abstract
Motivation: Accurate prediction of cancer drug response (CDR) is challenging due to the uncertainty of drug efficacy and heterogeneity of cancer patients. Strong evidences have implicated the high dependence of CDR on tumor genomic and transcriptomic profiles of individual patients. Precise identification of CDR is crucial in both guiding anti-cancer drug design and understanding cancer biology.
Results: In this study, we present DeepCDR which integrates multi-omics profiles of cancer cells and explores intrinsic chemical structures of drugs for predicting cancer drug response. Specifically, DeepCDR is a hybrid graph convolutional network consisting of a uniform graph convolutional network (UGCN) and multiple subnetworks. Unlike prior studies modeling hand-crafted features of drugs, DeepCDR automatically learns the latent representation of topological structures among atoms and bonds of drugs. Extensive experiments showed that DeepCDR outperformed state-of-the-art methods in both classification and regression settings under various data settings. We also evaluated the contribution of different types of omics profiles for assessing drug response. Furthermore, we provided an exploratory strategy for identifying potential cancer-associated genes concerning specific cancer types. Our results highlighted the predictive power of DeepCDR and its potential translational value in guiding disease-specific drug design.
