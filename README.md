This repository contains four Jupyter notebook (.ipynb) files along with the necessary datasets required to reproduce the experiments.

RUIP_BA_Voice.ipynb, RUIP_BA_Swipe.ipynb, and RUIP_BA_Drawing.ipynb:
These three notebooks implement the proposed RUIP-BA framework for the Voice, Swipe, and Drawing datasets. The current implementation is primarily configured, optimized, and experimentally tuned for the RP+DP setting of these datasets. Most model parameters and hyperparameters were selected based on this configuration.

While the same framework can also be applied to the plain, RP, or DP versions of the datasets, these settings may require additional tuning and re-optimization of model parameters and hyperparameters to achieve optimal performance.


Attack.ipynb: 
This notebook provides a standalone reimplementation of the ML-based attack experiments on the voice dataset. The attack framework incorporates machine learning (ML)-based reconstruction attacks using all three model architectures evaluated in this work, including the DNN-Regressor, the baseline GAN, and the stronger GAN architecture.
