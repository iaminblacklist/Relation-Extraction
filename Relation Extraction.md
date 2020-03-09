# Relation Extraction

## CNN

| **(2014)[Relation Classification via Convolutional Deep Neural Network](https://www.aclweb.org/anthology/C14-1220.pdf)(809)** | CNN                                                          |
| **(2015)[Relation Extraction: Perspective from Convolutional Neural Networks](https://www.aclweb.org/anthology/W15-1506.pdf)(272)** | **CNN +** **多粒度卷积核**                                   |
| **(2015)[Classifying Relations by Ranking with Convolutional Neural Networks](https://www.aclweb.org/anthology/P15-1061.pdf)(332)** | **CNN + ranking loss**                                       |
| **(2015)**[**Bidirectional Long Short-Term Memory Networks for Relation Classification**](https://www.aclweb.org/anthology/Y15-1009.pdf)**(112)** | **LSTM + 依存句法 + CNN + ranking loss**                     |
| **(2016)[Relation Classification via Multi-Level Attention CNNs](https://www.aclweb.org/anthology/P16-1123.pdf)(182)** | **CNN + Multi-level Attention + ranking loss**               |
| **(2017)**[**Joint entity and relation extraction based on a hybrid neural network**](https://www.sciencedirect.com/science/article/abs/pii/S0925231217301613)**(63)** | **Bi-LSTM(entity extraction) + CNN(relation classification)** |
| **(2019)**[**Knowledge-oriented convolutional neural network for causal relation extraction from natural language texts**](https://www.sciencedirect.com/science/article/abs/pii/S0957417418305177)**(16)** | **Knowledge-oriented Convolutional Neural Network (K-CNN)**  |

## LSTM

| **(2015)**[**Bidirectional Long Short-Term Memory Networks for Relation Classification**](https://www.aclweb.org/anthology/Y15-1009.pdf)**(112)** | **LSTM + 依存句法 + CNN + ranking loss**                     |
| **(2016)**[**Attention-Based Bidirectional Long Short-Term Memory Networks for Relation Classification**](https://www.aclweb.org/anthology/P16-2034.pdf)**(495)** | **Bi-LSTM + Attention**                                      |
| **(2016)**[**Bidirectional Recurrent Convolutional Neural Network for Relation Classification**](https://www.aclweb.org/anthology/P16-1072.pdf)**(82)** | **shortest dependency path (SDP) + Bi-LSTM + CNN**           |
| **(2017)**[**Joint entity and relation extraction based on a hybrid neural network**](https://www.sciencedirect.com/science/article/abs/pii/S0925231217301613)**(63)** | **Bi-LSTM(entity extraction) + CNN（relation classification）** |
| **(2017)**[**Combining Word-Level and Character-Level Representations for**](https://www.aclweb.org/anthology/W17-2606.pdf)**(11)** | **Bi-GRU + CNN**                                             |
| **(2017)**[**Cross-Sentence N-ary Relation Extraction with Graph LSTMs**](https://www.mitpressjournals.org/doi/abs/10.1162/tacl_a_00049)**(123)** | **graph LSTMs**                                              |
| **(2020)**[**Semantic relation extraction using sequential and tree-structured LSTM with attention**](https://www.sciencedirect.com/science/article/pii/S0020025519308515)**(2)** | **tree-structured LSTM + attention**                         |

## Attention

| **(2016)**[**Attention-Based Bidirectional Long Short-Term Memory Networks for Relation Classification**](https://www.aclweb.org/anthology/P16-2034.pdf)**(495)** | **Bi-LSTM + Attention**                               |
| **(2016)**[**Relation Classification via Multi-Level Attention CNNs**](https://www.aclweb.org/anthology/P16-1123.pdf)**(182)** | **CNN + Multi-level Attention + ranking loss**        |
| **(2017)**[**Designing an Adaptive Attention Mechanism for Relation Classification**](https://ieeexplore.ieee.org/abstract/document/7966407)**(12)** | **Entity-pair-based Attention Mechanism**             |
| **(2019)**[**Hybrid Attention-Based Prototypical Networks for Noisy Few-Shot Relation Classification**](https://www.aaai.org/ojs/index.php/AAAI/article/view/4604)**(16)** | **few-shot learning + hybrid attention-based models** |
| **(2020)**[**Semantic relation extraction using sequential and tree-structured LSTM with attention**](https://www.sciencedirect.com/science/article/pii/S0020025519308515)**(2)** | **tree-structured LSTM + attention**                  |
| **(2020)**[**Dynamic Prototype Selection by Fusing Attention Mechanism for Few-Shot Relation Classification**](https://link.springer.com/chapter/10.1007/978-3-030-41964-6_37) | **Attention + few-shot learning**                     |

## CRF

| **(2017)**[**Global Normalization of Convolutional Neural Networks for Joint Entity and Relation Classification**](https://arxiv.org/pdf/1707.07719.pdf)**(29)** | **linear-chain Conditional Random Field** |
| **(2018)**[**Joint entity recognition and relation extraction as a multi-head selection problem**](https://www.sciencedirect.com/science/article/abs/pii/S095741741830455X)**(30)** | **Conditional Random Field**              |

## **Distant Supervision**

| **(2017)**[**Distant supervision for relation extraction with sentence-level attention and entity descriptions**](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewPaper/14491)**(127)** | **Distant Supervision**                               |
| **(2018)[Adversarial learning for distant supervised relation extraction](http://centaur.reading.ac.uk/77404/)(75)** | **Adversarial training + Distant supervision**        |
| **(2018)**[**Robust Distant Supervision Relation Extraction via Deep Reinforcement Learning**](https://arxiv.org/pdf/1805.09927.pdf)**(49)** | **Distant supervision + deep reinforcement learning** |

## **Adversarial Training**

| **(2017)**[**Adversarial Training for Relation Extraction**](https://www.aclweb.org/anthology/D17-1187.pdf)**(80)** | **Adversarial training**                       |
| **(2018)[Adversarial learning for distant supervised relation extraction](http://centaur.reading.ac.uk/77404/)(75)** | **Adversarial training + Distant supervision** |
| **(2018)**[**DSGAN: Generative Adversarial Training for Distant Supervision Relation Extraction**](https://arxiv.org/abs/1805.09929)**(43)** | **DSGAN**                                      |

## Deep Reinforcement Learning

| **(2018)**[**Robust Distant Supervision Relation Extraction via Deep Reinforcement Learning**](https://arxiv.org/pdf/1805.09927.pdf)**(49)** | **Distant supervision +** **deep reinforcement learning** |
| **(2018)**[**Reinforcement Learning for Relation Classification From Noisy Data**](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/17151)**(92)** | **deep reinforcement learning**                           |
| **(2019)**[**A Hierarchical Framework for Relation Extraction with Reinforcement Learning**](https://www.aaai.org/ojs/index.php/AAAI/article/view/4688)**(20)** | **hierarchical reinforcement learning (HRL) framework**   |

## GCN

| **(2019)**[**A Walk-based Model on Entity Graphs for Relation Extraction**](https://arxiv.org/pdf/1902.07023.pdf)**(29)** | **graph-based neural network**   |
| **(2018)[Graph Convolution over Pruned Dependency Trees Improves Relation Extraction](https://arxiv.org/pdf/1809.10185.pdf)(79)** | **graph convolutional networks** |

## Few-Shot Learning

| **(2019)**[**Hybrid Attention-Based Prototypical Networks for Noisy Few-Shot Relation Classification**](https://www.aaai.org/ojs/index.php/AAAI/article/view/4604)**(16)** | **few-shot learning + hybrid attention-based models** |
| **(2020)**[**Dynamic Prototype Selection by Fusing Attention Mechanism for Few-Shot Relation Classification**](https://link.springer.com/chapter/10.1007/978-3-030-41964-6_37) | **Attention + few-shot learning**                     |

