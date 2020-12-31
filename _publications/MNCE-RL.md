---
title: "Reinforced Molecular Optimization with Neighborhood-Controlled Grammars" 
collection: publications
permalink: /publications/MNCE-RL
---
[[Paper](https://papers.nips.cc/paper/2020/file/5f268dfb0fbef44de0f668a022707b86-Paper.pdf)] [[Code](https://github.com/Zoesgithub/MNCE-RL)] [[Suppl](https://papers.nips.cc/paper/2020/file/5f268dfb0fbef44de0f668a022707b86-Supplemental.pdf)] 

## Abstract
A major challenge in the pharmaceutical industry is to design novel molecules with specific desired properties, especially when the property evaluation is costly. Here, we propose MNCE-RL, a graph convolutional policy network for molecular optimization with molecular neighborhood-controlled embedding grammars through reinforcement learning. We extend the original neighborhood-controlled embedding grammars to make them applicable to molecular graph generation and design an efficient algorithm to infer grammatical production rules from given molecules. The use of grammars guarantees the validity of the generated molecular structures. By transforming molecular graphs to parse trees with the inferred grammars, the molecular structure generation task is modeled as a Markov decision process where a policy gradient strategy is utilized. In a series of experiments, we demonstrate that our approach achieves state-of-the-art performance in a diverse range of molecular optimization tasks and exhibits significant superiority in optimizing molecular properties with a limited number of property evaluations.
