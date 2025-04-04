---
title: "Deep-Learning Methods for Particle Reconstruction at the LFHCal"
excerpt: "CPSC 483 (Fall 2024) Class Project <br/> <img src = '/images/lfhcal_figure.png'>"
collection: portfolio
---

CERN’s Large Forward Hadron Calorimeter (LFHCal) measures the energy of hadronic particles generated in collisions. The LFHCal's complex geometry, pile-up noise, and overlapping particle showers pose substantial challenges for particle reconstruction. Traditional methods poorly scale and fail to accurately recover the full energy of the clusters. To address this issue, I proposed and led a project exploring machine-learning techniques for particle reconstruction at the LFHCal. Starting with foundational methods to ensure interpretability, I demonstrated that an approach combining quadratic regression and k-means clustering attained high accuracy and achieved remarkable robustness against Gaussian noise. This method provides an elegant solution with attractive simplicity and competitive performance. I presented these findings at a general meeting of the LFHCal collaboration in May 2024. The promising outcomes and the enthusiasm of the physicist team motivated me to explore more advanced methodologies. In an ongoing project, I am developing graph-based deep learning techniques that use a trainable adjacency matrix to embed node features into a highly expressive latent space. I hypothesize that by iteratively re-embedding and constructing $k$-nearest neighbor graphs, the model will produce more clearly separated clusters, ultimately outperforming my initial approach. However, this method presents significant challenges regarding transparency, particularly in determining whether the model is learning the correct underlying patterns or laws of physics. 

<a href="https://github.com/selma-m/DLG-for-Particle-Reconstruction">GitHub repository</a>
<a href="files/483_project_report.pdf"> Project report </a>
