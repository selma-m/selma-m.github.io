---
title: "Exploring the Manifold of Neural Networks Using Diffusion Geometry"
excerpt: "Summer Project <br/> <img src = 'images/schematic_v5.png'>"
collection: portfolio
---

This work, supervised by Yale Professors Smita Krishnaswamy and Ian Adelstein, focused on understanding how different network architectures represent and process information, particularly in high-dimensional spaces. Hypothesizing that neural networks can be largely characterized by the data representations they create, we proposed to generate a low-dimensional manifold of neural networks organized by their hidden-layer representations of a dataset. My work involved training and fine-tuning ResNets and CNNs; characterizing the structure of their embeddings using diffusion spectral entropy (DSE), which measures the number of significant eigendirections of the data; and analyzing signals on the manifold. I found that high-performing neural networks—across different architectures—exhibit high DSE, which suggests a more pronounced cluster structure. Moreover, I showed that test accuracy was a low-frequency signal on the manifold, meaning that it is structured by network performance. This insight offers a more systematic method for architecture search: hyperparameters extrapolated from models in the high-accuracy region of the learned manifold could lead to high-performing models. We submitted a manuscript presenting our results at the 28th International Conference on Artificial Intelligence and Statistics in October 2024.

<a href='https://arxiv.org/abs/2411.12626'>Paper</a>
