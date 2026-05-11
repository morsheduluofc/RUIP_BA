This repository contains two Jupyter notebook (.ipynb) files along with the necessary datasets required to reproduce the experiments.

RUIP_BA.ipynb: This notebook implements the proposed RUIP-BA framework. The current implementation is primarily configured, optimized, and experimentally tuned for the voice dataset using Random Projection (RP) combined with both Laplace and Gaussian noise mechanisms. Most model parameters and hyperparameters were selected based on this experimental setting.
Although the same framework can also be applied to other datasets (e.g., swipe and drawing datasets), the parameters and hyperparameters may require additional adjustment and re-tuning to achieve optimal performance for those modalities.

GAN.ipynb: This notebook provides a standalone reimplementation of the GAN-based attack experiments on the voice dataset. The attack framework incorporates machine learning (ML)-based reconstruction attacks using all three model architectures evaluated in this work, including the DNN-Regressor, the baseline GAN, and the stronger GAN architecture.
