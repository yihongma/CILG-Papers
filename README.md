## Class-Imbalanced Learning on Graphs (CILG)

This repository contains a curated list of papers focused on **<u>C</u>lass-<u>I</u>mbalanced <u>L</u>earning on <u>G</u>raphs (CILG)**. The papers are categorized based on their methodological contributions across Data-Level methods (Data Interpolation, Adversarial Generation, Pseudo-Labeling) and Algorithm-Level methods (Model and Training Refinement, Loss Function Engineering, Post-hoc Adjustments). Many papers contribute to multiple aspects, as indicated in their listings.

We aim to keep this list up to date. If you come across any errors or papers that should be included, please feel free to open an issue or submit a pull request.

## Survey Paper

[**Class-Imbalanced Learning on Graphs: A Survey**](https://arxiv.org/pdf/2304.04300). 

[Yihong Ma](https://yihongma.github.io/), [Yijun Tian](http://tianyijun.com/), [Nuno Moniz](https://www.dcc.fc.up.pt/~nmoniz/), and [Nitesh V. Chawla](https://niteshchawla.nd.edu/).

If you find this repository useful in your research, please cite:
```bibtex
@article{ma2023class,
  title={Class-Imbalanced Learning on Graphs: A Survey},
  author={Ma, Yihong and Tian, Yijun and Moniz, Nuno and Chawla, Nitesh V},
  journal={arXiv preprint arXiv:2304.04300},
  year={2023}
}
```

## Papers

Legend for method categories:
- Data-Level Methods:
  - [D.I.] Data Interpolation
  - [A.G.] Adversarial Generation
  - [P.L.] Pseudo-Labeling
- Algorithm-Level Methods:
  - [M.R.] Model and Training Refinement
  - [L.F.] Loss Function Engineering
  - [P.A.] Post-hoc Adjustments

Primary contributions are marked with ■, secondary contributions with □.

### 2024
* **Graph Neural Network with Curriculum Learning for Imbalanced Node Classification** (*Neurocomputing*) [[paper]](https://arxiv.org/pdf/2202.02529.pdf)
  * Methods: [D.I.] ■, [M.R.] □

### 2023

* **Rethinking Semi-Supervised Imbalanced Node Classification from Bias-Variance Decomposition** (*NeurIPS*) [[paper]](https://arxiv.org/pdf/2310.18765.pdf) [[code]](https://github.com/yanliang3612/ReVar)
  * Methods: [M.R.] ■, [L.F.] □

* **Semantic-aware Node Synthesis for Imbalanced Heterogeneous Information Networks** (*CIKM*) [[paper]](https://arxiv.org/pdf/2302.14061.pdf) [[code]](https://github.com/XYGaoG/SNS)
  * Methods: [D.I.] ■, [M.R.] □, [L.F.] □

* **GraphSHA: Synthesizing Harder Samples for Class-Imbalanced Node Classification** (*KDD*) [[paper]](https://arxiv.org/pdf/2306.09612.pdf) [[code]](https://github.com/wenzhilics/GraphSHA)
  * Methods: [D.I.] ■, [M.R.] □

* **When Sparsity Meets Contrastive Models: Less Graph Data Can Bring Better Class-Balanced Representations** (*ICML*) [[paper]](https://proceedings.mlr.press/v202/zhang23o/zhang23o.pdf) [[code]](https://www.dropbox.com/sh/8jaq9zekzl3khni/AAA0kNDs_UMxj4YbTEKKyiXna?dl=0)
  * Methods: [M.R.] ■, [L.F.] □

* **Imbalanced Node Classifcation Beyond Homophilic Assumption** (*IJCAI*) [[paper]](https://www.ijcai.org/proceedings/2023/0848.pdf)
  * Methods: [D.I.] ■, [M.R.] □, [L.F.] □

* **INS-GNN: Improving graph imbalance learning with self-supervision** (*Information Sciences*) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0020025523005042) [[code]](https://github.com/juanxin/INS-GNN)
  * Methods: [P.L.] ■, [M.R.] □, [L.F.] □

* **Balanced neighbor exploration for semi-supervised node classification on imbalanced graph data** (*Information Sciences*) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0020025523002529)
  * Methods: [M.R.] ■

* **ImGCL: Revisiting Graph Contrastive Learning on Imbalanced Node Classification** (*AAAI*) [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26319/26091)
  * Methods: [M.R.] ■, [L.F.] □

* **GraphSR: A Data Augmentation Algorithm for Imbalanced Node Classification** (*AAAI*) [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25622/25394)
  * Methods: [P.L.] ■, [M.R.] □

### 2022

* **Co-Modality Graph Contrastive Learning for Imbalanced Node Classification** (*NeurIPS*) [[paper]](https://openreview.net/pdf?id=f_kvHrM4Q0) [[code]](https://github.com/graphprojects/CM-GCL)
  * Methods: [M.R.] ■, [L.F.] □

* **Anonymity Can Help Minority: A Novel Synthetic Data Over-sampling Strategy on Multi-label Graphs** (*ECML PKDD*) [[paper]](https://2022.ecmlpkdd.org/wp-content/uploads/2022/09/sub_1027.pdf)
  * Methods: [A.G.] ■, [L.F.] □

* **GraphMixup: Improving Class-Imbalanced Node Classification by Reinforcement Mixup and Self-supervised Context Prediction** (*ECML/PKDD*) [[paper]](https://2022.ecmlpkdd.org/wp-content/uploads/2022/09/sub_375.pdf) [[code]](https://github.com/LirongWu/GraphMixup)
  * Methods: [D.I.] ■, [M.R.] □, [L.F.] □

* **LTE4G: Long-Tail Experts for Graph Neural Networks** (*CIKM*) [[paper]](https://arxiv.org/pdf/2208.10205.pdf) [[code]](https://github.com/SukwonYun/LTE4G)
  * Methods: [M.R.] ■, [P.A.] □

* **Distance-wise Prototypical Graph Neural Network for Imbalanced Node Classification** (*MLG*) [[paper]](http://www.mlgworkshop.org/2022/papers/MLG22_paper_6707.pdf) [[code]](https://github.com/YuWVandy/DPGNN)
  * Methods: [P.L.] ■, [M.R.] □

* **FACS-GCN: Fairness-Aware Cost-Sensitive Boosting of Graph Convolutional Networks** (*IJCNN*) [[paper]](https://www.cse.msu.edu/~ptan/papers/FACS-GCN.pdf) [[code]](https://github.com/frsantosp/FACS-GCN)
  * Methods: [L.F.] ■, [A.G.] □, [M.R.] □

* **A Kernel Propagation-Based Graph Convolutional Network Imbalanced Node Classification Model on Graph Data** (*ICNSC*) [[paper]](https://ieeexplore.ieee.org/iel7/10004025/10004026/10004183.pdf)
  * Methods: [M.R.] ■, [L.F.] □

* **Effective-aggregation Graph Convolutional Network for Imbalanced Classification** (*ICNSC*) [[paper]](https://ieeexplore.ieee.org/iel7/10004025/10004026/10004069.pdf)
  * Methods: [M.R.] ■

* **Attention and Cost-Sensitive Graph Neural Network for Imbalanced Node Classification** (*ICNSC*) [[paper]](https://ieeexplore.ieee.org/iel7/10004025/10004026/10004144.pdf)
  * Methods: [M.R.] ■, [L.F.] □

* **GATSMOTE: Improving Imbalanced Node Classification on Graphs via Attention and Homophily** (*Mathematics*) [[paper]](https://www.mdpi.com/2227-7390/10/11/1799)
  * Methods: [D.I.] ■, [M.R.] □, [L.F.] □

* **ALLIE: Active Learning on Large-scale Imbalanced Graphs** (*WWW*) [[paper]](https://assets.amazon.science/b0/3c/5d25ba6a44a9aeef450083b41e88/allie-active-learning-on-large-scale-imbalanced-graphs.pdf)
  * Methods: [M.R.] ■, [L.F.] □, [P.A.] □

* **TAM: Topology-Aware Margin Loss for Class-Imbalanced Node Classification** (*ICML*) [[paper]](https://proceedings.mlr.press/v162/song22a/song22a.pdf) [[code]](https://github.com/Jaeyun-Song/TAM)
  * Methods: [L.F.] ■

### 2021

* **Exploring Self-training for Imbalanced Node Classification** (*ICONIP*) [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-92307-5_4)
  * Methods: [P.L.] ■

* **Topology-Imbalance Learning for Semi-Supervised Node Classification** (*NeurIPS*) [[paper]](https://proceedings.neurips.cc/paper/2021/file/fa7cdfad1a5aaf8370ebeda47a1ff1c3-Paper.pdf) [[code]](https://github.com/victorchen96/ReNode)
  * Methods: [L.F.] ■

* **ImGAGN: Imbalanced Network Embedding via Generative Adversarial Graph Networks** (*KDD*) [[paper]](https://arxiv.org/pdf/2106.02817.pdf) [[code]](https://github.com/Leo-Q-316/ImGAGN)
  * Methods: [A.G.] ■

* **GraphENS: Neighbor-Aware Ego Network Synthesis for Class-Imbalanced Node Classification** (*ICLR*) [[paper]](https://openreview.net/pdf?id=MXEl7i-iru) [[code]](https://github.com/JoonHyung-Park/GraphENS)
  * Methods: [D.I.] ■, [M.R.] □

* **GraphSMOTE: Imbalanced Node Classification on Graphs with Graph Neural Networks** (*WSDM) [[paper]](https://arxiv.org/pdf/2103.08826.pdf) [[code]](https://github.com/TianxiangZhao/GraphSmote)
  * Methods: [D.I.] ■, [M.R.] □, [L.F.] □

### 2020

* **Multi-Class Imbalanced Graph Convolutional Network Learning** (*IJCAI*) [[paper]](https://www.ijcai.org/proceedings/2020/0398.pdf) [[code]](https://github.com/codeshareabc/DRGCN)
  * Methods: [A.G.] ■, [M.R.] □, [L.F.] □

### 2018

* **ImVerde: Vertex-Diminished Random Walk for Learning Imbalanced Network Representation** (*Big Data*) [[paper]](https://arxiv.org/pdf/1804.09222.pdf) [[code]](https://github.com/jwu4sml/ImVerde)
  * Methods: [M.R.] ■

* **SPARC: Self-Paced Network Representation for Few-Shot Rare Category Characterization** (*KDD*) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3219819.3219968) [[code]](http://publish.illinois.edu/daweizhou/files/2019/10/SPARC.zip)
  * Methods: [P.L.] ■, [M.R.] □, [L.F.] □

* **RSDNE: Exploring Relaxed Similarity and Dissimilarity from Completely-Imbalanced Labels for Network Embedding** (*AAAI*) [[paper]](https://cdn.aaai.org/ojs/11242/11242-13-14770-1-2-20201228.pdf) [[code]](https://github.com/zhengwang100/RSDNE-python)
  * Methods: [M.R.] ■, [L.F.] □


## Acknowledgement

This page has been created and is maintained by [Yihong Ma](https://yihongma.github.io/) (yma5@nd.edu)