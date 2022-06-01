# Learning with Signatures

J. de Curtò, I. de Zarzà, Hong Yan, Carlos T. Calafate (2022). Learning with Signatures. [arXiv:2204.07953](https://arxiv.org/pdf/2204.07953)

We provide a python notebook (also exported to HTML format for ease of readibility) to reproduce the experiments in Section 4; 100% accuracy on AFHQ, MNIST and CIFAR10 **assuming we can determine at test time which probably good optimal scale factor to use for each category**. Computation is done at the CPU, with the use of very few labeled examples and without learned hyperparameters. Here weights (that is, scale factors) are computed by Definition 4, which is equivalent to only use the objective that is convex with equality to zero in Equation 8. RMSE Signature is used as score function.
