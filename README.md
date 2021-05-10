# Model Compression And Acceleration

>Sorted out some papers related to deep neural network model compression and acceleration for easy reference. They are mainly divided into five methods:
- [Pruning](#1-Pruning)
- [Quantization](#2-Quantization)
- [Knowledge Distillation](#3-Knowledge-Distillation)
- [Matrix Decomposition](#4-Matrix-Decomposition)
- [Neural Architecture Search](#5-Neural-Architecture-Search)

## 1. Pruning
>Pruning is to remove the redundant parameters in the network while reducing the amount of calculation while not affecting the network performance as much as possible, so as to realize the compression of the model and the acceleration of the reasoning.
### 1.1 Weight Pruning
- 2015-NIPS-[Learning both Weights and Connections for Efficient Neural Networks](https://arxiv.org/abs/1506.02626)
- 2016-NIPS-[Dynamic Network Surgery for Efficient DNNs](https://arxiv.org/abs/1608.04493)
- 2016-ICLR-[Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding](https://arxiv.org/abs/1510.00149)**`(Best Paper)`**
- 2017-CVPR-[Designing Energy-Efficient Convolutional Neural Networks using Energy-Aware Pruning](https://arxiv.org/abs/1611.05128)

### 1.2 Filter Pruning
- 2017-ICLR-[Pruning Filters for Efficient ConvNets](https://arxiv.org/abs/1608.08710)
- 2017-ICLR-[Pruning Convolutional Neural Networks for Resource Efficient Inference](https://arxiv.org/abs/1611.06440)
- 2017-ICCV-[Learning Efficient Convolutional Networks through Network Slimming](https://arxiv.org/abs/1708.06519)
- 2019-ICCV-[Accelerate CNN via Recursive Bayesian Pruning](https://arxiv.org/abs/1812.00353)
- 2019-CVPR-[Filter Pruning via Geometric Median for Deep Convolutional Neural Networks Acceleration](https://arxiv.org/abs/1811.00250)

### 1.3 Reconstruction-Error-Based or Data-Driven Pruning
- 2016-[Network Trimming: A Data-Driven Neuron Pruning Approach towards Efficient Deep Architectures](https://arxiv.org/abs/1607.03250)
- 2017-ICCV-[ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression](https://arxiv.org/abs/1707.06342)
- 2017-ICCV-[Channel Pruning for Accelerating Very Deep Neural Networks](https://arxiv.org/abs/1707.06168)
- 2018-ECCV-[Data-Driven Sparse Structure Selection for Deep Neural Networks](https://arxiv.org/abs/1707.01213)
- 2018-NIPS-[Discrimination-aware Channel Pruning for Deep Neural Networks](https://arxiv.org/abs/1810.11809)

### 1.4 Auto Pruning
- 2018-ECCV-[AMC: AutoML for Model Compression and Acceleration on Mobile Devices](https://arxiv.org/abs/1802.03494)
- 2018-ECCV-[NetAdapt: Platform-Aware Neural Network Adaptation for Mobile Applications](https://arxiv.org/abs/1804.03230v2)
- 2019-ICLR-[Slimmable Neural Networks](https://arxiv.org/abs/1812.08928)
- 2019-ICCV-[Universally Slimmable Networks and Improved Training Techniques](https://arxiv.org/abs/1903.05134)
- 2019-ICCV-[MetaPruning: Meta Learning for Automatic Neural Network Channel Pruning](https://arxiv.org/abs/1903.10258)
- 2019-NIPS`(Workshop)`-[AutoSlim: Towards One-Shot Architecture Search for Channel Numbers](https://arxiv.org/abs/1903.11728)

### 1.5 Thinking and Analysis
- 2018-ICLR`(Workshop)`-[To prune, or not to prune: exploring the efficacy of pruning for model compression](https://arxiv.org/abs/1710.01878)
- 2019-ICLR-[The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://arxiv.org/abs/1803.03635)**`(Best Paper)`**
- 2019-ICLR-[Rethinking the Value of Network Pruning](https://arxiv.org/abs/1810.05270)

## 2. Quantization
>Waiting for update...

## 3. Knowledge Distillation
>Waiting for update...

## 4. Matrix Decomposition
>Waiting for update...

## 5. Neural Architecture Search
- 2019-CVPR-[ChamNet: Towards Efficient Network Design through Platform-Aware Model Adaptation](https://arxiv.org/abs/1812.08934v1)
- 2019-CVPR-[FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search](https://arxiv.org/abs/1812.03443)
