# Self-Attention and Intersample Attention Transformer (SAINT) - PyTorch
## Contrastive Learning for Tabular Data

Paper: [https://arxiv.org/pdf/2106.01342.pdf](https://arxiv.org/pdf/2106.01342.pdf)

Implementation of Self-Attention Transformer, a simple way to achieve SOTA in classification with tabular data (even beats XGBoost!). SAINT performs attention over both rows and columns, and entails an enhanced embedding method. Of particular interest here is the contrastive self-supervised pre-training method proposed by the author's papers for use when labels are scarce

The base model architecture is motivated by the seminal paper [Attention is All You Need](https://arxiv.org/abs/1706.03762).
