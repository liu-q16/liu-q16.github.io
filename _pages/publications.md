---
title: "Publications"
permalink: /publications/
author_profile: true
---

## Highlighted papers

(For a full list see [below](#full-list) or go to [Google Scholar](https://scholar.google.com/citations?user=StBWeZgAAAAJ&hl=zh-CN))

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


<style>
.pub{font-size:16px;}
</style>

## Full List
1. <div class="pub">Density estimation using deep generative neural networks <br>
<b>Qiao Liu</b>, Jiaze Xu, Rui Jiang and Wing Hung Wong.
<i>Proceedings of the National Academy of Sciences of the United States of America</i>. 2021. [<a href="https://liu-q16.github.io/publications/Roundtrip">Abstract</a>][<a href="https://liu-q16.github.io/files/Roundtrip.pdf">PDF</a>][<a href="https://github.com/kimmo1019/Roundtrip">Code</a>]</div>

1. <div class="pub">Simultaneous deep generative modeling and clustering of single cell genomic data<br>
<b>Qiao Liu</b>, Shengquan Chen, Rui Jiang and Wing Hung Wong.
<i>Nature Machine Intelligence</i>. 2021. (accepted) [<a href="https://liu-q16.github.io/publications/scDEC">Abstract</a>][<a href="https://liu-q16.github.io/files/scDEC.pdf">PDF</a>][<a href="https://github.com/kimmo1019/scDEC">Code</a>]</div>

1. <div class="pub">Incorporating Gene Expression in Genome-wide Prediction of Chromatin Accessibility via Deep Learning<br>
<b>Qiao Liu</b>, Wing Hung Wong and Rui Jiang.
<i>Genomics, Proteomics & Bioinformatics</i>. 2021. (accepted) [<a href="https://liu-q16.github.io/publications/DeepCAGE">Abstract</a>][<a href="https://liu-q16.github.io/files/DeepCAGE.pdf">PDF</a>][<a href="https://github.com/kimmo1019/DeepCAGE">Code</a>]</div>

1. <div class="pub">Reinforced Molecular Optimization with Neighborhood-Controlled Grammars<br>
Chencheng Xu, <b>Qiao Liu</b>, Minlie Huang, Tao Jiang.
<i>NeurIPS</i>. 2020. [<a href="https://liu-q16.github.io/publications/MNCE-RL">Abstract</a>][<a href="https://liu-q16.github.io/files/MNCE-RL.pdf">PDF</a>][<a href="https://github.com/Zoesgithub/MNCE-RL">Code</a>]</div>

1. <div class="pub">Feature-Enhanced Graph Networks for Genetic Mutational Prediction Using Histopathological Images in Colon Cancer<br>
Kexin Ding, <b>Qiao Liu</b>, Edward Lee, Mu Zhou, Aidong Lu, Shaoting Zhang.
<i>MICCAI</i>. 2020. [<a href="https://liu-q16.github.io/publications/DeepCAGE">Abstract</a>][<a href="https://liu-q16.github.io/files/DeepCAGE.pdf">PDF</a>][<a href="https://github.com/kimmo1019/DeepCAGE">Code</a>]</div>

1. <div class="pub">Cancer Drug Response Prediction via a Hybrid Graph Convolutional Network <br>
<b>Qiao Liu</b>, Zhiqiang Hu and Mu Zhou.
<i>Bioinformatics</i>. 2020. (in submission)[<a href="https://liu-q16.github.io/publications/DeepCDR">Abstract</a>][<a href="https://liu-q16.github.io/files/DeepCDR.pdf">PDF</a>][<a href="https://github.com/kimmo1019/DeepCDR">Code</a>]</div>

1. <div class="pub">Quantifying Functional Impacts of Regulatory Variants with Multi-task Bayesian Neural Network <br>
Chencheng Xu, <b>Qiao Liu</b>, Jianyu Zhou, Minzhu Xie, Jianxing Feng and Tao Jiang.
<i>Bioinformatics</i>. 2019. (Q1)[<a href="https://liu-q16.github.io/publications/MtBNN">Abstract</a>][<a href="https://liu-q16.github.io/files/MtBNN.pdf">PDF</a>][<a href="https://github.com/Zoesgithub/MtBNN">Code</a>]</div>

1. <div class="pub">A Decentralized Systemfor Medical Data Management via Blockchain <br>
Qingzhu Yang, <b>Qiao Liu</b>, Hairong Lv.
<i>Journal of Internet Technology</i>. 2020, 21(5): 1335-1345.[<a href="https://liu-q16.github.io/publications/BlockChain">Abstract</a>][<a href="https://liu-q16.github.io/files/BlockChain.pdf">PDF</a>]</div>

1. <div class="pub">Mstree: A Multispecies Coalescent Approach for Estimating Ancestral Population Size and Divergence Time During Speciation with Gene Flow <br>
Junfeng Liu, <b>Qiao Liu</b>, Qingzhu Yang.
<i>Genome Biology and Evolution</i>. 2020, 12(5): 715-719[<a href="https://liu-q16.github.io/publications/MStree">Abstract</a>][<a href="https://liu-q16.github.io/files/MStree.pdf">PDF</a>][<a href="https://github.com/liujunfengtop/MStree">Code</a>]</div>

1. <div class="pub">hicGAN Infers Super Resolution Hi-C Data With Generative Adversarial Networks <br>
<b>Qiao Liu</b>, Hairong Lv, Rui Jiang.
<i>ISMB/Bioinformatics</i>. 2019, 35(14):i99-i107.(conference acceptance rate:18.9%, Q1)[<a href="https://liu-q16.github.io/publications/hicGAN">Abstract</a>][<a href="https://liu-q16.github.io/files/hicGAN.pdf">PDF</a>][<a href="https://github.com/kimmo1019/hicGAN">Code</a>]</div>

1. <div class="pub">Automatically Structuring on Chinese Ultrasound Report of Cerebrovascular Diseases via Natural Language Processing <br>
Pengyu Chen<sup>*</sup>, <b>Qiao Liu</b><sup>*</sup>, Hairong Lv and Xiaolu Fei.
<i>IEEE Access</i>. 2019.7: 89043-89050. (Co-first author, Q1)[<a href="https://liu-q16.github.io/publications/CRF">Abstract</a>][<a href="https://liu-q16.github.io/files/CRF.pdf">PDF</a>]</div>

1. <div class="pub">EpiFIT: Functional Interpretation of Transcription Factors based on Combination of Sequence and Epigenetic Information <br>
Shaoming Song, Hongfei Cui, <b>Qiao Liu</b>, Rui Jiang.
<i>Quantitative Biology</i>. 2019, 1-11.[<a href="https://liu-q16.github.io/publications/EpiFIT">Abstract</a>][<a href="https://liu-q16.github.io/files/EpiFIT.pdf">PDF</a>]</div>

1. <div class="pub">DeepHistone: a Deep Learning Approach to Predicting Histone Modifications] <br>
Qijin Yin, Mengmeng Wu, <b>Qiao Liu</b>, Rui Jiang.
<i>BMC Genomics</i>. 2019,20(2):193. (Q2)[<a href="https://liu-q16.github.io/publications/DeepHistone">Abstract</a>][<a href="https://liu-q16.github.io/files/DeepHistone.pdf">PDF</a>][<a href="https://github.com/QijinYin/DeepHistone">Code</a>]</div>

1. <div class="pub">Chromatin Accessibility Prediction via a Hybrid Deep Convolutional Neural Network <br>
<b>Qiao Liu</b>, Fei Xia, Qijin Yin, Rui Jiang.
<i>Bioinformatics</i>. 2017, 34(5): 732-738. (Q1)[<a href="https://liu-q16.github.io/publications/Deopen">Abstract</a>][<a href="https://liu-q16.github.io/files/Deopen.pdf">PDF</a>][<a href="https://github.com/kimmo1019/Deopen">Code</a>]</div>

1. <div class="pub">A Sequence-based Method to Predict the Impact of Regulatory Variants Using Random Forest <br>
<b>Qiao Liu</b>, Minxing Gan, Rui Jiang.
<i>BMC Systems Biology</i>. 2017, 11(2): 7. (Q2)[<a href="https://liu-q16.github.io/publications/kmerforest">Abstract</a>][<a href="https://liu-q16.github.io/files/kmerforest.pdf">PDF</a>][<a href="https://github.com/kimmo1019/kmerforest">Code</a>]</div>

1. <div class="pub">Protein Folding Optimization Based on 3D off-lattice Model via an Improved Artificial Bee Colony Algorithm <br>
Bai Li, Mu Lin, <b>Qiao Liu</b>, Ya Li.
<i>Journal of Molecular Modeling</i>. 2015, 21(10): 261. (Q2)[<a href="https://liu-q16.github.io/publications/BE-ABC">Abstract</a>][<a href="https://liu-q16.github.io/files/BE-ABC.pdf">PDF</a>][<a href="https://github.com/kimmo1019/BE-ABC">Code</a>]</div>

<div class="pub">
(* denotes equal contribution)
</div>




