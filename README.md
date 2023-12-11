# high-dim-ml-f23
Research project: Adapting linear attention and random features to query/key distributions

Author: Xingchen (Estella) Ye (xy2527@columbia.edu)

Course Title: IEOR E6617 Machine Learning and High-dimensional Data Mining, Fall 2023

Instructor: Prof. Krzysztof Choromanski

# Abstract
This research focuses on adapting linear attention mechanisms to approximated query and key vectors in high-dimensional spaces. Methods are proposed to approximate the means (q0,k0) and covariance matrices (Σq,Σk) of queries and keys, under the assumption that sufficient samples can be drawn from the true distributions.

Then, we explore methods to linearize the softmax attention kernel, introducing two random feature mappings φsin/cos(x,w) and φ(x, w), proposed in the works of Rahimi & Recht (2007) and Choromanski et al. (2021). Our research includes an analysis of the linearity of these methods and their unbiased nature. Additionally, we incorporate the squared norm approximation technique to efficiently compute the norms of queries and keys.

Through series of experiments, we examine the impact of varying sample sizes on the attention mechanism. Then, we demonstrate how the specific underlying distributions, N(q0,Σ1),N(k0,Σk), influence the behavior of the attention approximation. The results are visualized through a series of figures, providing valuable insights into the behavior of attention approximations under different distribution constructions.
