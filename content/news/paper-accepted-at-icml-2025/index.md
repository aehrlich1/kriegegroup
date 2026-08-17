---
title: "Paper accepted at ICML 2025"
url: "/paper-accepted-at-icml-2025/"
date: 2025-05-14T10:46:27
author: "Lorenz Kummer"
summary: "We’re thrilled to share that our paper “Weisfeiler and Leman Go Gambling: Why Expressive Lottery Tickets Win” by Lorenz Kummer, Samir Moustafa, Anatol Ehrlich, Franka Bause, Nikolaus Suess, Wilfried Gansterer and Nils Kriege has been accpted at the 42nd International Conference on Machine Learning, July 13th-19th 2025, Vancouver, Canada! This work bridges two important areas […]"
image: "/images/news/icml-2025-paper.png"
---

We’re thrilled to share that our paper “Weisfeiler and Leman Go Gambling: Why Expressive Lottery Tickets Win” by *Lorenz Kummer*, *Samir Moustafa*, *Anatol Ehrlich*, *Franka Bause*, *Nikolaus Suess*, *Wilfried Gansterer* and *Nils Kriege* has been accpted at the 42nd International Conference on Machine Learning, July 13th-19th 2025, Vancouver, Canada!

This work bridges two important areas of machine learning: the **Lottery Ticket Hypothesis (LTH)** and **Graph Neural Network (GNN) expressivity**. While LTH suggests that large models contain smaller sparse subnetworks (“winning tickets”) that can perform equally well, its theoretical grounding in the GNN domain has remained limited—until now.

**Key Contributions:**

- We show that a winning ticket in GNNs must retain the **ability to distinguish certain non-isomorphic graphs**.
- We introduce the **Strong Expressive Lottery Ticket Hypothesis (SELTH)**, formally proving that sparse, trainable subnetworks can match the expressivity of full GNNs.
- **Convergence & Generalization**: High expressivity at initialization is linked to better gradient diversity, indicative of **faster convergence**, and **stronger generalization**.
- **Irrecoverable Loss**: Pruning without regard to expressivity can lead to **permanent loss of predictive power**—especially harmful in domains like drug discovery where misclassifying toxic stereoisomers has real-world consequences.
- **Empirical Support**: Across 13,500 experiments on 10 benchmark datasets, we show that **expressive sparse GNNs typically outperform less expressive ones**, even when heavily pruned.

Our work lays the foundation for **principled pruning strategies** in GNNs that **preserve expressive power**. It also provides a theoretical lens to evaluate whether a sparse GNN is likely to succeed *before* training—critical for efficiency in large-scale graph learning.

We believe this opens the door to **more efficient, trustworthy, and interpretable** GNN models—especially important in sensitive applications like molecular property prediction and drug design.
