---
title: "hicGAN Infers Super Resolution Hi-C Data With Generative Adversarial Networks"
collection: publications
permalink: /publications/hicGAN
venue: "ISMB 2019/Bioinformatics"
date: 2019-7-20
citation: '<b>Qiao Liu</b>, Hairong Lv, and Rui Jiang. <i>The 27th conference on Intelligent Systems for Molecular Biology</i>. <b>ISMB 2019</b>.'
---
[[Paper](https://academic.oup.com/bioinformatics/article-abstract/35/14/i99/5529246)] [[Code](https://github.com/kimmo1019/hicGAN)][[Slide](http://kimmo1019.github.io/files/hicGAN_slides.pdf)]


## Abstract
Motivation: Hi-C is a genome-wide technology for investigating 3D chromatin conformation by measuring physical contacts between pairs of genomic regions. The resolution of Hi-C data di-rectly impacts the effectiveness and accuracy of downstream analysis such as identifying topo-logically associating domains (TADs) and meaningful chromatin loops. High resolution Hi-C data are valuable resources which implicate the relationship between 3D genome conformation and function, especially linking distal regulatory elements to their target genes. However, high resolu-tion Hi-C data across various tissues and cell types are not always available due to the high se-quencing cost. It is therefore indispensable to develop computational approaches for enhancing the resolution of Hi-C data.
Results: We proposed hicGAN, an open-sourced framework, for inferring high resolution Hi-C data from low resolution Hi-C data with generative adversarial networks (GANs). To the best of our knowledge, this is the first study to apply GANs to 3D genome analysis. We demonstrate that hicGAN effectively enhances the resolution of low resolution Hi-C data by generating matri-ces that are highly consistent with the original high resolution Hi-C matrices. A typical scenario of usage for our approach is to enhance low resolution Hi-C data in new cell types, especially where the high resolution Hi-C data are not available. Our study not only presents a novel ap-proach for enhancing Hi-C data resolution, but also provides fascinating insights into disclosing complex mechanism underlying the formation of chromatin contacts.
