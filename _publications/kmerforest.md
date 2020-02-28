---
title:"A Sequence-based Method to Predict the Impact of Regulatory Variants Using Random Forest" 
collection: publications
permalink: /publications/kmerforest
venue: "BMC Systems Biology"
date: 2017-03-14
citation: '<b>Qiao Liu</b>, Mingxin Gan and Rui Jiang <i>BMC Systems Biology, 2017</i>.'
---
[[Paper](https://bmcsystbiol.biomedcentral.com/articles/10.1186/s12918-017-0389-1)] [[Code](https://github.com/kimmo1019/kmerforest)]


## Abstract
Background:Most disease-associated variants identified by genome-wide association studies (GWAS) exist in noncoding regions. In spite of the common agreement that such variants may disrupt biological functions of their hosting regulatory elements, it remains a great challenge to characterize the risk of a genetic variant within the implicated genome sequence. Therefore, it is essential to develop an effective computational model that is not only capable of predicting the potential risk of a genetic variant but also valid in interpreting how the function of the genome is affected with the occurrence of the variant.
Results:We developed a method named kmerForest that used a random forest classifier with k-mer counts to predict accessible chromatin regions purely based on DNA sequences. We demonstrated that our method outperforms existing methods in distinguishing known accessible chromatin regions from random genomic sequences. Furthermore, the performance of our method can further be improved with the incorporation of sequence conservation features. Based on this model, we assessed importance of the k-mer features by a series of permutation experiments, and we characterized the risk of a single nucleotide polymorphism (SNP) on the function of the genome using the difference between the importance of the k-mer features affected by the occurrence of the SNP. We conducted a series of experiments and showed that our model can well discriminate between pathogenic and normal SNPs. Particularly, our model correctly prioritized SNPs that are proved to be enriched for the binding sites of FOXA1 in breast cancer cell lines from previous studies.
Conclusions:We presented a novel method to interpret functional genetic variants purely base on DNA sequences. The proposed k-mer based score offers an effective means of measuring the impact of SNPs on the function of the genome, and thus shedding light on the identification of genetic risk factors underlying complex traits and diseases.
