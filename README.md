## Class-Imbalanced Learning on Graphs (CILG)

This repository contains a curated list of papers focused **on Class-Imbalanced Learning on Graphs (CILG)**. We have organized them into two primary groups: (1) [data-level methods](#data-level-methods) and (2) [algorithm-level methods](#algorithm-level-methods). Data-level methods are further subdivided into (i) [data interpolation](#data-interpolation), (ii) [adversarial generation](#adversarial-generation), and (iii) [pseudo-labeling](#pseudo-labeling). Algorithm-level methods are categorized into (i) [model refinement](#model-refinement), (ii) [loss function engineering](#loss-function-engineering), and (iii) [post-hoc adjustments](#post-hoc-adjustments).

We aim to keep this list up to date. If you come across any errors or papers that should be included, please feel free to open an issue or submit a pull request. We appreciate your contributions in maintaining the quality and relevance of this repository.

## Survey Paper

[**Class-Imbalanced Learning on Graphs: A Survey**](https://arxiv.org/pdf/2304.04300). 

[Yihong Ma](https://yihongma.github.io/), [Yijun Tian](http://tianyijun.com/), [Nuno Moniz](https://www.dcc.fc.up.pt/~nmoniz/), and [Nitesh V. Chawla](https://niteshchawla.nd.edu/).

#### If you find this repository useful in your research, we would greatly appreciate it if you could cite our paper in your work. Thank you for your support!

```bibtex
@article{ma2023class,
  title={Class-Imbalanced Learning on Graphs: A Survey},
  author={Ma, Yihong and Tian, Yijun and Moniz, Nuno and Chawla, Nitesh V},
  journal={arXiv preprint arXiv:2304.04300},
  year={2023}
}
```

## Data-Level Methods

### Data Interpolation

* **Rethinking Semi-Supervised Imbalanced Node Classification from Bias-Variance Decomposition**, in *NeurIPS* 2023. [\[pdf\]](https://arxiv.org/pdf/2310.18765.pdf) [\[code\]](https://github.com/yanliang3612/ReVar)

* **Semantic-aware Node Synthesis for Imbalanced Heterogeneous Information Networks**, in *CIKM* 2023. [\[pdf\]](https://arxiv.org/pdf/2302.14061.pdf)

* **HOVER: Homophilic Oversampling via Edge Removal for Class-Imbalanced Bot Detection on Graphs**, in *CIKM* 2023. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3583780.3615264)

* **GraphSHA: Synthesizing Harder Samples for Class-Imbalanced Node Classification**, in *KDD* 2023. [\[pdf\]](https://arxiv.org/pdf/2306.09612.pdf) [\[code\]](https://github.com/wenzhilics/GraphSHA)

* **Imbalanced Node Classifcation Beyond Homophilic Assumption**, in *IJCAI* 2023. [\[pdf\]](https://www.ijcai.org/proceedings/2023/0848.pdf)

* **GraphMixup: Improving Class-Imbalanced Node Classification by Reinforcement Mixup and Self-supervised Context Prediction**, in *ECML/PKDD* 2023. [\[pdf\]](https://2022.ecmlpkdd.org/wp-content/uploads/2022/09/sub_375.pdf) [\[code\]](https://github.com/LirongWu/GraphMixup)

* **GATSMOTE: Improving Imbalanced Node Classification on Graphs via Attention and Homophily**, in *Mathematics* 2022. [\[pdf\]](https://www.mdpi.com/2227-7390/10/11/1799)

* **Graph Neural Network with Curriculum Learning for Imbalanced Node Classification**, in *arXiv* 2022. [\[pdf\]](https://arxiv.org/pdf/2202.02529.pdf)

* **GraphENS: Neighbor-Aware Ego Network Synthesis for Class-Imbalanced Node Classification**, in *ICLR* 2021. [\[pdf\]](https://openreview.net/pdf?id=MXEl7i-iru) [\[code\]](https://github.com/JoonHyung-Park/GraphENS)

* **GraphSMOTE: Imbalanced Node Classification on Graphs with Graph Neural Networks**, in *WSDM* 2021. [\[pdf\]](https://arxiv.org/pdf/2103.08826.pdf) [\[code\]](https://github.com/TianxiangZhao/GraphSmote)

### Adversarial Generation

* **Anonymity Can Help Minority: A Novel Synthetic Data Over-sampling Strategy on Multi-label Graphs**, in *ECML/PKDD* 2022. [\[pdf\]](https://2022.ecmlpkdd.org/wp-content/uploads/2022/09/sub_1027.pdf)

* **ImGAGN: Imbalanced Network Embedding via Generative Adversarial Graph Networks**, in *KDD* 2021. [\[pdf\]](https://arxiv.org/pdf/2106.02817.pdf) [\[code\]](https://github.com/Leo-Q-316/ImGAGN)

### Pseudo-Labeling

* **GraphSR: A Data Augmentation Algorithm for Imbalanced Node Classification**, in *AAAI* 2023. [\[pdf\]](https://arxiv.org/pdf/2302.12814)

* **Distance-wise Prototypical Graph Neural Network for Imbalanced Node Classification**, in *MLG* 2022. [\[pdf\]](http://www.mlgworkshop.org/2022/papers/MLG22_paper_6707.pdf) [\[code\]](https://github.com/YuWVandy/DPGNN)

* **Exploring Self-training for Imbalanced Node Classification**, in *ICONIP* 2021. [\[pdf\]](https://link.springer.com/chapter/10.1007/978-3-030-92307-5_4)

* **SPARC: Self-Paced Network Representation for Few-Shot Rare Category Characterization**, in *KDD* 2018. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3219819.3219968) [\[code\]](http://www.google.com/url?q=http%3A%2F%2Fpublish.illinois.edu%2Fdaweizhou%2Ffiles%2F2019%2F10%2FSPARC.zip&sa=D&sntz=1&usg=AOvVaw0Ua6DhuOfhYWplG0XNAlZl)

## Algorithm-Level Methods

Please note that certain papers may be relevant to more than one category.

### Model Refinement

* **QTIAH-GNN: Quantity and Topology Imbalance-aware Heterogeneous Graph Neural Network for Bankruptcy Prediction**, in *KDD* 2023. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3580305.3599479)

* **ImGCL: Revisiting Graph Contrastive Learning on Imbalanced Node Classification**, in *AAAI* 2023. [\[pdf\]](https://arxiv.org/pdf/2205.11332.pdf)

* **Co-Modality Graph Contrastive Learning for Imbalanced Node Classification**, in *NeurIPS* 2022. [\[pdf\]](https://openreview.net/pdf?id=f_kvHrM4Q0) [\[code\]](https://github.com/graphprojects/CM-GCL)

* **LTE4G: Long-Tail Experts for Graph Neural Networks**, in *CIKM* 2022. [\[pdf\]](https://arxiv.org/pdf/2208.10205.pdf) [\[code\]](https://github.com/SukwonYun/LTE4G)

* **A Kernel Propagation-Based Graph Convolutional Network Imbalanced Node Classification Model on Graph Data**, in *ICNSC* 2022. [\[pdf\]](https://ieeexplore.ieee.org/iel7/10004025/10004026/10004183.pdf)

* **Effective-aggregation Graph Convolutional Network for Imbalanced Classification**, in *ICNSC* 2022. [\[pdf\]](https://ieeexplore.ieee.org/iel7/10004025/10004026/10004069.pdf)

* **Attention and Cost-Sensitive Graph Neural Network for Imbalanced Node Classification**, in *ICNSC* 2022. [\[pdf\]](https://ieeexplore.ieee.org/iel7/10004025/10004026/10004144.pdf)

* **Diving into Unified Data-Model Sparsity for Class-Imbalanced Graph Representation Learning**, in *GLFrontiers* 2022. [\[pdf\]](https://arxiv.org/pdf/2210.00162.pdf) [\[code\]](https://www.dropbox.com/sh/8jaq9zekzl3khni/AAA0kNDs_UMxj4YbTEKKyiXna?dl=0)

* **Network Embedding with Completely-imbalanced Labels**, in *TKDE* 2020 . [\[pdf\]](https://arxiv.org/pdf/2007.03545.pdf) [\[code\]](https://github.com/zhengwang100/RECT)

* **RSDNE: Exploring Relaxed Similarity and Dissimilarity from Completely-Imbalanced Labels for Network Embedding**, in *AAAI* 2018. [\[pdf\]](https://cdn.aaai.org/ojs/11242/11242-13-14770-1-2-20201228.pdf) [\[code\]](https://github.com/zhengwang100/RSDNE-python)

* **ImVerde: Vertex-Diminished Random Walk for Learning Imbalanced Network Representation**, in *Big Data* 2018. [\[pdf\]](https://arxiv.org/pdf/1804.09222.pdf) [\[code\]](https://github.com/jwu4sml/ImVerde)

### Loss Function Engineering

* **QTIAH-GNN: Quantity and Topology Imbalance-aware Heterogeneous Graph Neural Network for Bankruptcy Prediction**, in *KDD* 2023. [\[pdf\]](https://dl.acm.org/doi/pdf/10.1145/3580305.3599479)

* **ImGCL: Revisiting Graph Contrastive Learning on Imbalanced Node Classification**, in *AAAI* 2023. [\[pdf\]](https://arxiv.org/pdf/2205.11332.pdf)

* **TAM: Topology-Aware Margin Loss for Class-Imbalanced Node Classification**, in *ICML* 2022. [\[pdf\]](https://proceedings.mlr.press/v162/song22a/song22a.pdf) [\[code\]](https://github.com/Jaeyun-Song/TAM)

* **Co-Modality Graph Contrastive Learning for Imbalanced Node Classification**, in *NeurIPS* 2022. [\[pdf\]](https://openreview.net/pdf?id=f_kvHrM4Q0) [\[code\]](https://github.com/graphprojects/CM-GCL)

* **FACS-GCN: Fairness-Aware Cost-Sensitive Boosting of Graph Convolutional Networks**, in *IJCNN* 2022. [\[pdf\]](https://www.cse.msu.edu/~ptan/papers/FACS-GCN.pdf) [\[code\]](https://github.com/frsantosp/FACS-GCN)

* **Attention and Cost-Sensitive Graph Neural Network for Imbalanced Node Classification**, in *ICNSC* 2022. [\[pdf\]](https://ieeexplore.ieee.org/iel7/10004025/10004026/10004144.pdf)

* **Diving into Unified Data-Model Sparsity for Class-Imbalanced Graph Representation Learning**, in *GLFrontiers* 2022. [\[pdf\]](https://arxiv.org/pdf/2210.00162.pdf) [\[code\]](https://www.dropbox.com/sh/8jaq9zekzl3khni/AAA0kNDs_UMxj4YbTEKKyiXna?dl=0)

* **Topology-Imbalance Learning for Semi-Supervised Node Classification**, in *NeurIPS* 2021. [\[pdf\]](https://proceedings.neurips.cc/paper/2021/file/fa7cdfad1a5aaf8370ebeda47a1ff1c3-Paper.pdf) [\[code\]](https://github.com/victorchen96/ReNode)

* **FRAUDRE: Fraud Detection Dual-Resistant to Graph Inconsistency and Imbalance**, in *ICDM* 2021. [\[pdf\]](https://ieeexplore.ieee.org/iel7/9678506/9678989/09679178.pdf) [\[code\]](https://github.com/FraudDetection/FRAUDRE)

### Post-hoc Adjustments

* **LTE4G: Long-Tail Experts for Graph Neural Networks**, in *CIKM* 2022. [\[pdf\]](https://arxiv.org/pdf/2208.10205.pdf) [\[code\]](https://github.com/SukwonYun/LTE4G)

* **Multi-Class Imbalanced Graph Convolutional Network Learning**, in *IJCAI* 2020. [\[pdf\]](https://www.ijcai.org/proceedings/2020/0398.pdf) [\[code\]](https://github.com/codeshareabc/DRGCN)

## Acknowledgement

This page has been created and is maintained by [Yihong Ma](https://yihongma.github.io/) (yma5@nd.edu).