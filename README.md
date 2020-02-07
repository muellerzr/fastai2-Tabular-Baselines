# fastai2 Tabular Baseline

The following repository has a few tested baselines for tabular datasets outside of the two `fastai` uses (Rossmann and ADULTs).
Along with these include a few popular techniques also used, and how `fastai` compares.


[Poker Hand Induction](https://www.kaggle.com/c/poker-rule-induction)

| Model | Test Accuracy (%) |
|:-------------------------:|:-----------------:|
| Decision Tree | 50% |
| Multi-layer perceptron | 50% |
| Deep Neural Decision Tree | 65.1% |
| TabNet | 99.3% |
| **fastai2** | **99.44%** |

[Sarcos Robotics Arm Inverse Dynamics](http://www.gaussianprocess.org/gpml/data/)

| Model | MSE | Number of Parameters |
|:-----------------------------:|:-----:|:--------------------:|
| Random Forest | 2.39 | 16.7K |
| Stochastic Decision Tree | 2.11 | 28K |
| Multi-Layer Perceptron | 2.13 | 0.14M |
| Adaptive Neural Tree Ensemble | 1.23 | 0.60M |
| Gradient Boosted Tree | 1.44 | 0.99M |
| TabNet-S | 1.25 | 6.3K |
| TabNet-M | 0.28 | 590K |
| TabNet-L | 0.14 | 1.75M |
| **fastai2** | **0.038** | **530K** |

[Higgs Boson](https://archive.ics.uci.edu/ml/datasets/HIGGS)

| Model | Test Accuracy (%) | Number of Parameters |
|:--------------------------------------------------:|:-----------------:|:--------------------:|
| **Sparse evolutionary trained multi-layer perceptron** | **78.47** | **81K** |
| Gradient boosted tree - S | 74.22 | 120K |
| Gradient boosted tree - M | 75.97 | 690K |
| Multi-layer perceptron | 78.44 | 2.04M |
| Gradient boosted tree - L | 76.98 | 6.96M |
| TabNet - S | 78.25 | 81K |
| **TabNet - M** | **78.84** | **660K** |
| **fastai2** | **76.94** | **530K** |
