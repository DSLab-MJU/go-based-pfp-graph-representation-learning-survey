# An experimental analysis of graph representation learning for Gene Ontology based protein function prediction

> This is a collection of articles about graph representation learning for Gene Ontology based protein function prediction.

- Our paper: [An experimental analysis of graph representation learning for Gene Ontology based protein function prediction](#)

## Table of Contents

- [Introduction](#introduction)
- [Survey Methodology](#survey-methodology)
- [Survey Papers](#survey-papers)

## Introduction
Protein function annotation is one of the most fundamental research topics in bioinformatics. Understanding functions of proteins is not only crucial for biological systems, but can also enhances in other aspects, such as drug discovery, disease therapies, agriculture or manufacturing. However, current manual protein annotation performed by experts is costly and time-consuming, which could not keep up with the huge number of newly proteins generated from high-throughput sequencing techniques.  Specifically, there are more than 249 million unreviewed proteins in the UniProtKB database, only around 570 thousand sequences are manually annotated until April 2024. Thus, the development of accurate and effective computational predictors for protein function prediction (PFP) is imperative to bridge this gap.


## Survey Methodology
We created a preliminary list of papers using Google Scholar and PubMed. The search queries were combinations of the following keywords: ``"protein function prediction"``, ``"protein function annotation"``,  ``"Gene Ontology"``,  ``"graph neural network"``, ``"graph representation learning"``, ``"graph embedding"``, and ``"deep learning"``. To focus on recent studies, we filtered out results published before 2019.

Initially, articles were selected based on their titles and abstracts. Subsequently, full-text papers were assessed to determine whether they qualify as a significant method for Gene Ontology based protein function prediction using graph embedding. Additionally, relevant papers cited in the selected ones underwent the same process to ensure a comprehensive literature review.

## Survey Papers

> There are various methods for protein function prediction based on graph representation learning. We categorized these methods into four groups: PPI network, Protein Structure, GO graph, Integrated graphs.

- [PPI network](#1-ppi-network)
- [Protein Structure](#2-protein-structure)
- [GO graph](#3-go-graph)
- [Integrated graphs](#4-integrated-graphs)

### 1. PPI network

> PPI network embedding only

**deepNF: deep network fusion for protein function prediction**  
*Gligorijević, V., Barot, M., & Bonneau, R.*  
[Bioinformatics, 2018]
[[Paper](https://academic.oup.com/bioinformatics/article/34/22/3873/5026651?ref=https://githubhelp.com)]

**MGEGFP: a multi-view graph embedding method for gene function prediction based on adaptive estimation with GCN**  
*Li, W., Zhang, H., Li, M., Han, M., & Yin, Y.*  
[Bioinformatics, 2022]
[[Paper](https://academic.oup.com/bib/article/23/5/bbac333/6659744)]

**DeepGraphGO: graph neural network for large-scale, multispecies protein function prediction**  
*You, R., Yao, S., Mamitsuka, H., & Zhu, S.*  
[Bioinformatics, 2021]
[[Paper](https://academic.oup.com/bioinformatics/article/37/Supplement_1/i262/6319663)]

> Integrating PPI embeddings with heterogeneous data sources

**DeepGO: predicting protein functions from sequence and interactions using a deep ontology-aware classifier**  
*Kulmanov, M., Khan, M. A., & Hoehndorf, R.*  
[Bioinformatics, 2018]
[[Paper](https://academic.oup.com/bioinformatics/article/34/4/660/4265461)]

**DeepFunc: a deep learning framework for accurate prediction of protein functions from protein sequences and interactions**  
*Zhang, F., Song, H., Zeng, M., Li, Y., Kurgan, L., & Li, M.*  
[Proteomics, 2019]
[[Paper](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/pdf/10.1002/pmic.201900019)]

**SDN2GO: an integrated deep learning model for protein function prediction**
*Cai, Y., Wang, J., & Deng, L.*  
[Frontiers in Bioengineering and Biotechnology, 2020]
[[Paper](https://www.frontiersin.org/journals/bioengineering-and-biotechnology/articles/10.3389/fbioe.2020.00391/full)]

**A deep learning framework for gene ontology annotations with sequence-and network-based information**  
*Zhang, F., Song, H., Zeng, M., Wu, F. X., Li, Y., Pan, Y., & Li, M.*  
[IEEE/ACM transactions on computational biology and bioinformatics, 2020]
[[Paper](https://ieeexplore.ieee.org/abstract/document/8967035)]

**Prot2GO: Predicting GO annotations from protein sequences and interactions**  
*Zhang, X., Wang, L., Liu, H., Zhang, X., Liu, B., Wang, Y., & Li, J.*  
[IEEE/ACM transactions on computational biology and bioinformatics, 2021]
[[Paper](https://ieeexplore.ieee.org/abstract/document/9667246)]

**MultiPredGO: deep multi-modal protein function prediction by amalgamating protein structure, sequence, and interaction information**  
*Giri, S. J., Dutta, P., Halani, P., & Saha, S.*  
[IEEE Journal of Biomedical and Health Informatics, 2020]
[[Paper](https://ieeexplore.ieee.org/abstract/document/9187929)]

**GONET: A Deep Network to Annotate Proteins via Recurrent Convolution Networks**  
*Li, J., Wang, L., Zhang, X., Liu, B., & Wang, Y.*  
[IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2020]
[[Paper](https://ieeexplore.ieee.org/abstract/document/9313235)]

**DeepFusionGO: Protein function prediction by fusing heterogeneous features through deep learning**  
*Huang, Z., Zheng, R., & Deng, L.*  
[IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2022]
[[Paper](https://ieeexplore.ieee.org/abstract/document/9994899)]

**MSF-PFP: A Novel Multisource Feature Fusion Model for Protein Function Prediction**  
*Li, X., Qian, Y., Hu, Y., Chen, J., Yue, H., & Deng, L.*  
[Journal of Chemical Information and Modeling, 2024]
[[Paper](https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c01794)]

### 2. Protein Structure



### 3. GO graph

### 4. Integrated graphs