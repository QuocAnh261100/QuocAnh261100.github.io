---
title: " High-Dimensional Bayesian Optimization via Random Projection of Manifold Subspaces"
collection: publications
category: conferences
permalink: /publication/RPMBO
# excerpt: "A differentible method for pruning at initialization aims to convert the hard discrete optimization of finding Node Path Balance sparse networks into a fast and easy-to-integrate differentiable optimization problem."
date: 2024-08-22
venue: 'Joint European Conference on Machine Learning and Knowledge Discovery in Databases'
# slidesurl: 'http://QuanNguyen-Tri.github.io/files/DPaI_poster.pdf'
paperurl: 'https://arxiv.org/pdf/2412.16554'
citation: '<b>Quoc-Anh Hoang Nguyen</b>, The Hung Tran'
---

Abstract
------

Bayesian Optimization (BO) is a popular approach to optimizing expensive-to-evaluate black-box functions. Despite the success of BO, its performance may decrease exponentially as the dimensionality increases. A common framework to tackle this problem is to assume that the objective function depends on a limited set of features that lie on a low-dimensional manifold embedded in the high-dimensional ambient space. The latent space can be linear or more generally nonlinear. To learn feature mapping, existing works usually use an encode-decoder framework which is either computationally expensive or susceptible to overfittting when the labeled data is limited. This paper proposes a new approach for BO in high dimensions by exploiting a new representation of the objective function. Our approach combines a random linear projection to reduce the dimensionality, with a representation learning of the nonlinear manifold. When the geometry of the latent manifold is available, a solution to exploit this geometry is proposed for representation learning. In contrast, we use a neural network. To mitigate overfitting by using the neural network, we train the feature mapping in a geometry-aware semi-supervised manner. Our approach enables efficient optimizing of BO's acquisition function in the low-dimensional space, with the advantage of projecting back to the original high-dimensional space compared to existing works in the same setting. Finally, we show empirically that our algorithm outperforms other high-dimensional BO baselines in various synthetic functions and real applications.

