# Learning with Signatures

The code in this repository corresponds to the article https://arxiv.org/abs/2204.07953

We provide a python notebook (also exported to HTML format for ease of readibility) to reproduce the experiments in Section 4 (100% accuracy on AFHQ, MNIST, CIFAR10 and Four Shapes). In this particular example, we assume we can correctly resolve the ambiguity at test time of which probably good optimal lambda to use, for instance using the same criteria used to derive the weights in Definition 4. Computation is done at the CPU, orders of magnitude faster than DL Methods and with no learned hyperparameters. Weights (that is, optimal scale factors) are computed analytically by Definition 4. RMSE Signature is used as score function.

## Citation
If you find the manuscript or notebook useful in your research, please cite the paper `https://arxiv.org/abs/2204.07953`.

    @article{decurto_and_dezarza22,
      title={{L}earning with {S}ignatures},
      author={{de Curt{\`o}}, J. and {de Zarz{\`a}}, I. and {Calafate}, Carlos T. and {Yan}, Hong},
      journal={arXiv:2204.07953},
      year={2022}
    }
    
## Acknowledgements
This work is part of CIMDA (Centre for Intelligent Multidimensional Data Analysis), HK Science Park, HK.

A joint Center between City University of Hong Kong and the University of Oxford.

Our work has been supported by HK Innovation and Technology Commission (InnoHK Project CIMDA) and HK Research Grants Council (Project CityU 11204821).
