# Model Compression And Acceleration

Sorted out some papers related to deep neural network model compression and acceleration for easy reference. They are mainly divided into five methods:
- [Pruning](#1-Pruning)
- Quantization
- Knowledge Distillation
- Matrix Decomposition
- Neural Architecture Search

## 1. Pruning
>Pruning is to remove the redundant parameters in the network without affecting the network performance as much as possible, and reduce the amount of calculation, so as to achieve the compression of the model and the acceleration of reasoning.
### 1.1 Weight Pruning
- 2015-NIPS-[Learning both Weights and Connections for Efficient Neural Networks](https://arxiv.org/abs/1506.02626)
- 2016-ICLR **`(Best Paper)`**-[Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding](https://arxiv.org/abs/1510.00149)
- 2016-NIPS-[Dynamic Network Surgery for Efficient DNNs](https://arxiv.org/abs/1608.04493)

### 1.2 Filter Pruning
- 2017-ICLR-[Pruning Filters for Efficient ConvNets](https://arxiv.org/abs/1608.08710)
