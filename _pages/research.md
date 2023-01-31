---
title: "Research"
permalink: /research/
author_profile: true
---

## Overview

The use of statistics is expanding rapidly inside and outside of academia, with unprecedented growth in computationally intensive areas using large datasets from novel sources. How to efficiently and accurately decipher complex relationships underlying the large-scale data setting from real-world problems remains an urgent challenge. In recent years, a confluence of advances in machine learning and statistics is fueling a new wave of innovation that is poised to improve the data aggregation, estimation, interpretation, and prediction. Many classical disciplines of statistics are being redefined and reinforced by the magnificent bloom of machine learning. My general research goal lies in this multi-disciplinary area where I have been devoting to developing practical statistical and machine learning tools with both significance in statistical theory and applications in real-world problems. In particular, I have been pursuing this research agenda by exploiting the <i>deep generative models</i> to tackle several important statistical problems, such as density estimation, causal inference, and likelihood-free Bayesian inference, with broad applications in computational biology.

My research goal is to fulfill the new theories and methodologies for solving both statistical problems and data science problems in computational biology by developing computationally efficient techniques from machine learning field. I have been developing pioneered frameworks for causal inference (<a href="https://arxiv.org/abs/2212.05925">arXiv 2022</a>), density estimation (<a href="https://www.pnas.org/doi/10.1073/pnas.2101344118">PNAS 2021</a>), using <i>deep generative models</i> and apply the relative techniques to various computational biology problems, which include genomic studies (<a href="https://www.nature.com/articles/s42256-021-00333-y">NMI 2021</a>, <a href="https://academic.oup.com/bib/article-abstract/24/1/bbac494/6858951?redirectedFrom=fulltext">BIB 2022</a>,<a href="https://academic.oup.com/bioinformatics/article/35/14/i99/5529246">ISMB/Bioinformatics 2019</a>), and pharmacology studies (<a href="https://academic.oup.com/bioinformatics/article/36/Supplement_2/i911/6055929">ECCB/Bioinformatcis 2020</a>,<a href="https://proceedings.neurips.cc/paper/2020/hash/5f268dfb0fbef44de0f668a022707b86-Abstract.html">NeurIPS 2020</a>). 



##  Representative works in Statistics

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

##  Representative works in Computational Biology

{% assign number_printed = 0 %}
{% for publi in site.data.biopublist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


<style>
.pub{font-size:16px;}
</style>

<!--
## Preprints

1. <div class="pub">DeepDrug: A general graph-based deep learning framework for drug-drug interactions and drug-target interactions prediction <br>
Qijin Yin, Xusheng Cao, Rui Fan, <b>Qiao Liu*</b>, Rui Jiang*, Wanwen Zeng* <br>
<a href="https://www.biorxiv.org/content/10.1101/2020.11.09.375626v2">bioRxiv 2022</a></div>

1. <div class="pub">Applications of Transformer-based Language Models in Bioinformatics: A Survey <br>
Shuang Zhang, Yuti Liu, Shuang Chen, <b>Qiao Liu</b>, Wanwen Zeng <br>
<a href="https://www.biorxiv.org/content/10.1101/2020.11.09.375626v2">bioRxiv 2022</a></div>

1. <div class="pub">Graph Convolutional Networks for Multi-modality Medical Imaging: Methods, Architectures, and Clinical Applications <br>
Kexin Ding, Mu Zhou, Zichen Wang, <b>Qiao Liu</b>, Corey W. Arnold, Shaoting Zhang, Dimitri N. Metaxas <br>
<a href="https://arxiv.org/abs/2202.08916">arXiv 2022</a></div>

1. <div class="pub">Mutual Information Learned Regressor: an Information-theoretic Viewpoint of Training Regression Systems <br>
Jirong Yi, Qiaosheng Zhang, Zhen Chen, <b>Qiao Liu</b>, Yaohua Wang <br>
Under submission</div>

## Peer-reviewed papers

1. <div class="pub">Deep generative modeling and clustering of single cell Hi-C data <br>
<b>Qiao Liu</b>, Wanwen Zeng, Wei Zhang, Sicheng Wang, Hongyang Chen, Rui Jiang, Mu Zhou and Shaoting Zhang <br>
<a href="https://www.biorxiv.org/content/10.1101/2022.07.19.500573v1">Briefings in Bioinformatics 2022 (accepted)</a></div>

1. <div class="pub">Multimodal single cell data integration challenge: results and lessons learned <br>
Christopher Lance, Malte D Luecken, Daniel B Burkhardt,..., <b>Qiao Liu</b>,...,Fabian J Theis <br>
<a href="https://proceedings.mlr.press/v176/lance22a.html">Proceedings of Machine Learning Research (JMLR) 2022</a></div>

1. <div class="pub"> Regulatory analysis of single cell multiome gene expression and chromatin accessibility data with scREG <br>
Zhana Duren, Fengge Chang, Fnu Naqing, Jingxue Xin, <b>Qiao Liu</b>, Wing Hung Wong <br>
<a href="https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02682-2">Genome Biology 2022</a></div>

1. <div class="pub"> AggEnhance: Aggregation Enhancement by Class Interior Points in Federated Learning with Non-IID Data <br>
Jinxiang Ou, Yunheng Shen, Feng Wang, <b>Qiao Liu</b>, Xuegong Zhang, Hairong Lv <br>
<a href="https://dl.acm.org/doi/abs/10.1145/3544495">ACM Transactions on Intelligent Systems and Technology 2022</a></div>

1. <div class="pub"> scGraph: a graph neural network-based approach to automatically identify cell types <br>
Qijin Yin, <b>Qiao Liu</b>, Zhuoran Fu, Rui Jiang <br>
<a href="https://academic.oup.com/bioinformatics/article-abstract/38/11/2996/6565313">Bioinformatics 2022</a></div>

1. <div class="pub"> DualGCN: a dual graph convolutional network model to predict cancer drug response <br>
Tianxing Ma, <b>Qiao Liu</b>, Haochen Li, Mu Zhou, Rui Jiang, Xuegong Zhang <br>
<a href="https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-022-04664-4">BMC bioinformatics 2022</a></div>

1. <div class="pub"> DeepCAGE: incorporating transcription factors in genome-wide prediction of chromatin accessibility <br>
<b>Qiao Liu</b>, Kui Hua, Xuegong Zhang, Wing Hung Wong, Rui Jiang<br>
<a href="https://www.sciencedirect.com/science/article/pii/S1672022922000249">Genomics, Proteomics & Bioinformatics 2022</a> [<a href="https://github.com/kimmo1019/DeepCAGE">Code</a>]</div>

1. <div class="pub"> Boost Neural Networks by Checkpoints <br>
Feng Wang, Guoyizhe Wei, <b>Qiao Liu</b>, Jinxiang Ou, Xian Wei, Hairong Lv<br>
<a href="https://proceedings.neurips.cc/paper/2021/hash/a40511cad8383e5ae8ddd8b855d135da-Abstract.html">NeurIPS 2021</a></div>

1. <div class="pub"> OpenAnnotate: a web server to annotate the chromatin accessibility of genomic regions <br>
Shengquan Chen, <b>Qiao Liu</b>, Xuejian Cui, Rui Jiang<br>
<a href="https://academic.oup.com/nar/article-abstract/49/W1/W483/6276912">Nucleic Acids Research 2021</a></div>

1. <div class="pub">Simultaneous deep generative modeling and clustering of single cell genomic data<br>
<b>Qiao Liu</b>, Shengquan Chen, Rui Jiang and Wing Hung Wong<br>
<a href="https://www.nature.com/articles/s42256-021-00333-y">Nature Machine Intelligence 2021</a> [<a href="https://liu-q16.github.io/publications/scDEC">Abstract</a>][<a href="https://liu-q16.github.io/files/scDEC.pdf">PDF</a>][<a href="https://github.com/kimmo1019/scDEC">Code</a>]</div>

1. <div class="pub">Density estimation using deep generative neural networks <br>
<b>Qiao Liu</b>, Jiaze Xu, Rui Jiang and Wing Hung Wong<br>
<a href="https://www.pnas.org/doi/abs/10.1073/pnas.2101344118">Proceedings of the National Academy of Sciences of the United States of America 2021</a> [<a href="https://liu-q16.github.io/publications/Roundtrip">Abstract</a>][<a href="https://liu-q16.github.io/files/Roundtrip.pdf">PDF</a>][<a href="https://github.com/kimmo1019/Roundtrip">Code</a>]</div>


1. <div class="pub">Cancer Drug Response Prediction via a Hybrid Graph Convolutional Network<br>
<b>Qiao Liu</b>, Zhiqiang Hu, Rui Jiang and Mu Zhou<br>
<a href="https://academic.oup.com/bioinformatics/article-abstract/36/Supplement_2/i911/6055929">Bioinformatics 2020</a> [<a href="https://liu-q16.github.io/publications/DeepCDR">Abstract</a>][<a href="https://liu-q16.github.io/files/DeepCDR.pdf">PDF</a>][<a href="https://github.com/kimmo1019/DeepCDR">Code</a>]</div>

1. <div class="pub">Feature-Enhanced Graph Networks for Genetic Mutational Prediction Using Histopathological Images in Colon Cancer<br>
Kexin Ding, <b>Qiao Liu</b>, Edward Lee, Mu Zhou, Aidong Lu, Shaoting Zhang<br>
<a href="https://link.springer.com/chapter/10.1007/978-3-030-59713-9_29">MICCAI 2020</a> 

1. <div class="pub">A Decentralized Systemfor Medical Data Management via Blockchain <br>
Qingzhu Yang, <b>Qiao Liu</b>, Hairong Lv<br>
<a href="https://jit.ndhu.edu.tw/article/view/2370">Journal of Internet Technology 2020</a> 

1. <div class="pub">Mstree: A Multispecies Coalescent Approach for Estimating Ancestral Population Size and Divergence Time During Speciation with Gene Flow <br>
Junfeng Liu, <b>Qiao Liu</b>, Qingzhu Yang<br>
<a href="https://academic.oup.com/gbe/article-abstract/12/5/715/5828937">Genome Biology and Evolution 2020</a> 

1. <div class="pub">Quantifying Functional Impacts of Regulatory Variants with Multi-task Bayesian Neural Network <br>
Chencheng Xu, <b>Qiao Liu</b>, Jianyu Zhou, Minzhu Xie, Jianxing Feng and Tao Jiang<br>
<a href="https://academic.oup.com/bioinformatics/article-abstract/36/5/1397/5613893">Bioinformatics 2019</a> 


1. <div class="pub">Reinforced Molecular Optimization with Neighborhood-Controlled Grammars<br>
Chencheng Xu, <b>Qiao Liu</b>, Minlie Huang, Tao Jiang<br>
<a href="https://proceedings.neurips.cc/paper/2020/hash/5f268dfb0fbef44de0f668a022707b86-Abstract.html">NeurIPS 2020</a> [<a href="https://github.com/Zoesgithub/MNCE-RL">Code</a>]</div>


1. <div class="pub">hicGAN Infers Super Resolution Hi-C Data With Generative Adversarial Networks <br>
<b>Qiao Liu</b>, Hairong Lv, Rui Jiang<br>
<a href="https://academic.oup.com/bioinformatics/article-abstract/35/14/i99/5529246">ISMB/Bioinformatics 2019</a> [<a href="https://liu-q16.github.io/publications/hicGAN">Abstract</a>][<a href="https://liu-q16.github.io/files/hicGAN.pdf">PDF</a>][<a href="https://github.com/kimmo1019/hicGAN">Code</a>]</div>

1. <div class="pub">Automatically Structuring on Chinese Ultrasound Report of Cerebrovascular Diseases via Natural Language Processing <br>
Pengyu Chen<sup>*</sup>, <b>Qiao Liu</b><sup>*</sup>, Hairong Lv and Xiaolu Fei<br>
<a href="https://ieeexplore.ieee.org/abstract/document/8736947/">IEEE Access 2019</a> (Co-first author)

1. <div class="pub">DeepHistone: a Deep Learning Approach to Predicting Histone Modifications] <br>
Qijin Yin, Mengmeng Wu, <b>Qiao Liu</b>, Rui Jiang<br>
<a href="https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-019-5489-4">BMC Genomics 2019</a> [<a href="https://github.com/QijinYin/DeepHistone">Code</a>]</div>

1. <div class="pub">EpiFIT: Functional Interpretation of Transcription Factors based on Combination of Sequence and Epigenetic Information <br>
Shaoming Song, Hongfei Cui, <b>Qiao Liu</b>, Rui Jiang<br>
<a href="https://link.springer.com/article/10.1007/s40484-019-0175-8">Quantitative Biology 2019</a>


1. <div class="pub">Chromatin Accessibility Prediction via a Hybrid Deep Convolutional Neural Network <br>
<b>Qiao Liu</b>, Fei Xia, Qijin Yin, Rui Jiang<br>
<a href="https://academic.oup.com/bioinformatics/article-abstract/34/5/732/4562336">Bioinformatics 2018</a> [<a href="https://liu-q16.github.io/publications/Deopen">Abstract</a>][<a href="https://liu-q16.github.io/files/Deopen.pdf">PDF</a>][<a href="https://github.com/kimmo1019/Deopen">Code</a>]</div>

1. <div class="pub">A Sequence-based Method to Predict the Impact of Regulatory Variants Using Random Forest <br>
<b>Qiao Liu</b>, Minxing Gan, Rui Jiang<br>
<a href="https://bmcsystbiol.biomedcentral.com/articles/10.1186/s12918-017-0389-1">BMC Systems Biology 2017</a> [<a href="https://github.com/kimmo1019/kmerforest">Code</a>]</div>

1. <div class="pub">Protein Folding Optimization Based on 3D off-lattice Model via an Improved Artificial Bee Colony Algorithm <br>
Bai Li, Mu Lin, <b>Qiao Liu</b>, Ya Li<br>
<a href="https://link.springer.com/article/10.1007/s00894-015-2806-y">Journal of Molecular Modeling 2015</a> [<a href="https://github.com/kimmo1019/BE-ABC">Code</a>]</div>

<div class="pub">
(* denotes equal contribution)
</div>

-->


