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
[Briefings in Bioinformatics, 2022]
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

> Experimental protein structures

**Structure-based protein function prediction using graph convolutional networks**  
*Gligorijević, V., Renfrew, P. D., Kosciolek, T., Leman, J. K., Berenberg, D., Vatanen, T., ... & Bonneau, R.*  
[Nature communications, 2021] 
[[Paper](https://www.nature.com/articles/s41467-021-23303-9)]

**PersGNN: applying topological data analysis and geometric deep learning to structure-based protein function prediction**  
*Swenson, N., Krishnapriyan, A. S., Buluc, A., Morozov, D., & Yelick, K.*  
[[Paper](https://arxiv.org/abs/2010.16027)]

> Predicted protein structures

**Accurate protein function prediction via graph attention networks with predicted structure information**  
*Lai, B., & Xu, J.*  
[Briefings in Bioinformatics, 2022]
[[Paper](https://academic.oup.com/bib/article-abstract/23/1/bbab502/6457163)]

**Struct2GO: protein function prediction based on graph pooling algorithm and AlphaFold2 structure information**  
*Jiao, P., Wang, B., Wang, X., Liu, B., Wang, Y., & Li, J.*  
[Bioinformatics, 2023]
[[Paper](https://academic.oup.com/bioinformatics/article-abstract/39/10/btad637/7320010)]

**Combining protein sequences and structures with transformers and equivariant graph neural networks to predict protein function**  
*Boadu, F., Cao, H., & Cheng, J.*  
[Bioinformatics, 2023]
[[Paper](https://academic.oup.com/bioinformatics/article/39/Supplement_1/i318/7210446)]

**GPSFun: geometry-aware protein sequence function predictions with language models**  
*Yuan, Q., Tian, C., Song, Y., Ou, P., Zhu, M., Zhao, H., & Yang, Y.*  
[Nucleic Acids Research, 2024]
[[Paper](https://academic.oup.com/nar/advance-article-abstract/doi/10.1093/nar/gkae381/7670905)]

> Combined protein structures

**Hierarchical graph transformer with contrastive learning for protein function prediction**  
*Gu, Z., Luo, X., Chen, J., Deng, M., & Lai, L.*  
[Bioinformatics, 2023]
[[Paper](https://academic.oup.com/bioinformatics/article-abstract/39/7/btad410/7208864)]

### 3. GO graph

> General GO term embedding

**DeepGOA: Predicting Gene Ontology Annotations of Proteins via Graph Convolutional Network**  
*Zhou, G., Wang, J., Zhang, X., & Yu, G.*  
[IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2019]
[[Paper](https://ieeexplore.ieee.org/abstract/document/8983075)]

**Predicting functions of maize proteins using graph convolutional network**  
*Zhou, G., Wang, J., Zhang, X., Guo, M., & Yu, G.*  
[BMC bioinformatics, 2020]
[[Paper](https://link.springer.com/article/10.1186/s12859-020-03745-6)]

**TALE: Transformer-based protein function Annotation with joint sequence--Label Embedding**  
*Cao, Y., & Shen, Y.*  
[Bioinformatics, 2021]
[[Paper](https://academic.oup.com/bioinformatics/article-abstract/37/18/2825/6182677)]

**An effective GCN-based hierarchical multi-label classification for protein function prediction**  
*Choi, K., Lee, Y., Kim, C., & Yoon, M.*  
[[Paper](https://arxiv.org/abs/2112.02810)]

**GCL-GO: A novel sequence-based hierarchy-aware method for protein function prediction**  
*Choi, K., Lee, Y., & Kim, C.*  
[IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2022]
[[Paper](https://academic.oup.com/nargab/article-abstract/4/1/lqac004/6520105)]

**PANDA: protein function prediction using domain architecture and affinity propagation**  
*Wang, Z., Zhao, C., Wang, Y., Sun, Z., & Wang, N.*  
[Scientific reports, 2018]
[[Paper](https://www.nature.com/articles/s41598-018-21849-1)]

**PANDA2: protein function prediction using graph neural networks**  
*Zhao, C., Liu, T., & Wang, Z.*  
[NAR Genomics and Bioinformatics, 2022]
[[Paper](https://academic.oup.com/nargab/article/3/1/lqab004/6540737)]

**PFresGO: an attention mechanism-based deep-learning approach for protein annotation by integrating gene ontology inter-relationships**  
*Pan, T., Li, C., Bi, Y., Wang, Z., Gasser, R. B., Purcell, A. W., ... & Song, J.*  
[Bioinformatics, 2023]
[[Paper](https://academic.oup.com/bioinformatics/article-abstract/39/3/btad094/7043095)]

**Protein function prediction with functional and topological knowledge of gene ontology**  
*Zhao, Y., Yang, Z., Hong, Y., Yang, Y., Wang, L., Zhang, Y., ... & Wang, J.*  
[IEEE Transactions on NanoBioscience, 2023] 
[[Paper](https://ieeexplore.ieee.org/abstract/document/10129977)]

**DeepGATGO: A Hierarchical Pretraining-Based Graph-Attention Model for Automatic Protein Function Prediction**  
*Li, Z., Jiang, C., & Li, J.*  
[22nd International Workshop on Data Mining in Bioinformatics.]
[[Paper](https://arxiv.org/abs/2307.13004)]

**Partial order relation--based gene ontology embedding improves protein function prediction**  
*Li, W., Wang, B., Dai, J., Kou, Y., Chen, X., Pan, Y., ... & Xu, Z. Z.*  
[Briefings in Bioinformatics, 2024]
[[Paper](https://academic.oup.com/bib/article/25/2/bbae077/7620910)]

### 4. Integrated graphs

> PPI and other networks

**Graph2GO: a multi-modal attributed network embedding method for inferring protein functions**  
*Fan, K., Guan, Y., & Zhang, Y.*  
[GigaScience, 2020]
[[Paper](https://academic.oup.com/gigascience/article/9/8/giaa081/5885490)]

**A deep learning framework for predicting protein functions with co-occurrence of GO terms**  
*Li, M., Shi, W., Zhang, F., Zeng, M., & Li, Y.*  
[IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2022]
[[Paper](https://ieeexplore.ieee.org/abstract/document/9764369)]

**Protein function prediction using graph neural network with multi-type biological knowledge**  
*Shuai, Y., Wang, W., Li, Y., Zeng, M., & Li, M.*  
[IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2023]
[[Paper](https://ieeexplore.ieee.org/abstract/document/10385760)]

> Heteregenerous networks

**PSPGO: Cross-species heterogeneous network propagation for protein function prediction**  
*Wu, K., Wang, L., Liu, B., Liu, Y., Wang, Y., & Li, J.*  
[IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2022]
[[Paper](https://ieeexplore.ieee.org/abstract/document/9921345)]

**HNetGO: protein function prediction via heterogeneous network transformer**  
*Zhang, X., Guo, H., Zhang, F., Wang, X., Wu, K., Qiu, S., ... & Li, J.*  
[Briefings in Bioinformatics, 2023]
[[Paper](https://academic.oup.com/bib/article-abstract/24/6/bbab556/7323467)]

**OntoProtein: Protein Pretraining With Gene Ontology Embedding**  
*Zhang, N., Bi, Z., Liang, X., Cheng, S., Hong, H., Deng, S., ... & Chen, H.*  
[ICLR, 2022]
[[Paper](https://arxiv.org/abs/2201.11147)]

**Integrating Heterogeneous Biological Networks and Ontologies for Improved Protein Function Prediction with Graph Neural Networks**  
*Tran, N. C., & Gao, J. X.*  
[IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2023]
[[Paper](https://ieeexplore.ieee.org/abstract/document/10385281)]

**Predicting Protein Functions Based on Heterogeneous Graph Attention Technique**  
*Zhao, Y., Yang, Z., Wang, L., Zhang, Y., Lin, H., & Wang, J.*  
[IEEE Journal of Biomedical and Health Informatics, 2024]
[[Paper](https://ieeexplore.ieee.org/abstract/document/10423114)]

> Protein structure and GO graph

**TALE-cmap: Protein function prediction based on a TALE-based architecture and the structure information from contact map**  
*Qiu, X. Y., Wu, H., & Shao, J.*  
[Computers in Biology and Medicine, 2022]
[[Paper](https://www.sciencedirect.com/science/article/pii/S0010482522006734)]

**SLPFA: Protein Structure-Label Embedding Attention Network for Protein Function Annotation**  
*Zhang, Q., Liu, J., Yang, F., Yang, Z., & Feng, J.*  
[IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2023]
[[Paper](https://ieeexplore.ieee.org/abstract/document/10385633)]

**GNNGO3D: Protein function prediction based on 3d structure and functional hierarchy learning**  
*Zhang, L., Jiang, Y., & Yang, Y.*  
[IEEE Transactions on Knowledge and Data Engineering, 2023]
[[Paper](https://ieeexplore.ieee.org/abstract/document/10313062)]

**POLAT: Protein function prediction based on soft mask graph network and residue-Label ATtention**  
*Liu, Y., Zhang, Y., Chen, Z., & Peng, J.*  
[Computational Biology and Chemistry, 2024]
[[Paper](https://www.sciencedirect.com/science/article/pii/S1476927124000525)]