---
title:          Solving Discrete (Semi) Unbalanced Optimal Transport with Equivalent Transformation Mechanism and KKT-Multiplier Regularization
date:           2025-12-05 00:01:00 +0800
selected:       true
pub:            "Thirty-Ninth Annual Conference on Neural Information Processing Systems"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-custom badge-secondary">CCF A Conference</span><span class="badge badge-pill badge-custom badge-warning">Poster</span>'
pub_date:       "2025"

abstract: >-
    Semi-Unbalanced Optimal Transport (SemiUOT) shows great promise in matching two probability measures by relaxing one of the marginal constraints. Previous solvers often incorporate an entropy regularization term, which can result in inaccurate matching solutions. To address this issue, we focus on determining the marginal probability distribution of SemiUOT with KL divergence using the proposed Equivalent Transformation Mechanism (ETM) approach. Furthermore, we extend the ETM-based method into exploiting the marginal probability distribution of Unbalanced Optimal Transport (UOT) with KL divergence for validating its generalization. Once the marginal probabilities of UOT/SemiUOT are determined, they can be transformed into a classical Optimal Transport (OT) problem. Moreover, we propose a KKT-Multiplier regularization term combined with Multiplier Regularized Optimal Transport (MROT) to achieve more accurate matching results. We conduct several numerical experiments to demonstrate the effectiveness of our proposed methods in addressing UOT/SemiUOT problems.


cover:          assets/images/covers/etm.png
authors:
  - Weiming Liu
  - Xinting Liao†
  - Jun Dan
  - Fan Wang
  - Hua Yu
  - Junhao Dong
  - Shunjie Dong
  - Lianyong Qi
  - Yew-Soon Ong

links:
  Code: https://github.com/XeniaLLL/ETM.git
  Paper: https://neurips.cc/virtual/2025/loc/san-diego/poster/115733
#  Poster: assets/images/poster/icml2024-ws.jpeg
  Cite: assets/bibtex/liao2025etm.bib
---
