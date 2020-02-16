---
title: "Quantifying Functional Impact of Noncoding Variants with Multi-task Bayesian Neural Network"
collection: publications
permalink: /publications/MtBNN
venue: "Bioinformatics"
date: 2019-11-06
citation: 'Chencheng Xu, <b>Qiao Liu</b>, Jianyu Zhou, Minzhu Xie, Jianxing Feng and Tao Jiang. <i>Bioinformatics, 2019</i>.'
---
[[Paper](https://academic.oup.com/bioinformatics/advance-article-abstract/doi/10.1093/bioinformatics/btz767/5613893)] [[Code](https://github.com/Zoesgithub/MtBNN)]


## Abstract
Motivation:Advances in high-throughput genotyping and sequencing technologies during recent years have revealed essential roles of noncoding regions in gene regulation. Genome-wide association studies suggested that a large proportion of risk variants are located in noncoding regions and remain unexplained by current expression quantitative trait loci catalogs. Interpreting the causal effects of these genetic modifications is crucial but difficult owing to our limited knowledge of how regulatory elements function. Although several computational methods have been designed to prioritize regulatory variants that substantially impact human phenotypes, few of them achieve consistently high performance even when large scale multi-omic data are integrated.
Results:We propose a novel multi-task framework based on Bayesian deep neural networks, MtBNN, to quantify the deleterious impact of single nucleotide polymorphisms in noncoding genomic regions. With the high-efficiency provided by the multi-task Bayesian framework to integrate information from different sources, MtBNN is capable of extracting features from genomic sequences of large-scale chromatin-profiling data, such as chromatin accessibility and transcript factor binding affinities, and calculating the distribution of the probability that a noncoding variant disrupts regulatory activities. A series of comprehensive experiments show that MtBNN quantifies the functional impact of cis-regulatory variations with high accuracy, including expression quantitative trait locus, DNase I sensitivity quantitative trait locus and functional genetic variants located within ATAC-peaks that affect the accessibility of the corresponding peak, and achieves significantly better performance than the existing methods. Moreover, MtBNN has applications in the discovery of potentially causal disease-associated SNPs, thus helping fine-map the GWAS SNPs.
