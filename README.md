# Learning with Signatures

J. de Curtò, I. de Zarzà, Hong Yan, Carlos T. Calafate (2022). Learning with Signatures. arXiv:2204.07953.

We provide a python notebook (also exported to HTML format for ease of readibility) to reproduce the experiments in Section 4 (100% accuracy on AFHQ, MNIST and CIFAR10 assuming we can determine at test time which probably good optimal scale factor to use for each category). Computation is done at the CPU, orders of magnitude faster than DL Methods and with no learned hyperparameters. Weights (that is, optimal scale factors) are computed analytically by Definition 4. RMSE Signature is used as score function.
