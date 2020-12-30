### Overview

This repo contains assorted notes and experiments related to the impact of regularization and pruning on model compression.

As detailed further in the notes section, the experiments are related to:
- Compare L1, L2, Group Lasso Regularization methods
- Compare various pruning schedules

The observations include:
- The number of zero weights following training with and without pruning/regularization
- The convergence of loss function with and without pruning/regularization
- The distribution of weights in each kernel of a CNN with and without pruning/regularization

### Significance

Especially in resource-constrained environments (e.g. time, power, memory), such as perception systems on space rovers, conservation and efficient allocation of such resources is crucial. Model compression is focused on reducing the computational cost, memory, and latency of deep learning application, while preserving its function. By applying techniques such as quantization, weight sharing, and pruning, the memory taken up by weights of a neural network can be reduced by 90%. Similarly, regularization methods during training play a role in pushing unused weights toward 0, thus reducing the memory they take up.
