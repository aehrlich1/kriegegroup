---
title: "Paper Accepted at LoG 2024"
url: "/paper-accepted-at-log-2024/"
date: 2024-12-04T12:46:00
author: "Franka Bause"
summary: "The paper “Preventing Representation Rank Collapse in MPNNs by Splitting the Computational Graph” was accepted at the Learning on Graphs Conference (LoG) 2024!"
image: "/images/uploads/2024/12/log.png"
---

The paper “[Preventing Representational Rank Collapse in MPNNs by Splitting the Computational Graph](https://openreview.net/forum?id=DOh3hW1OZu)” by *Andreas Roth, Franka Bause, Nils Kriege, and Thomas Liebig* was accepted at the [LoG 2024](https://logconference.org/) conference! It proposes a method to prevent representational rank collapse in message-passing neural networks (MPNNs) by splitting a graph into a multi-relational graph with multiple edge types and operating on these using multi-relational split MPNNs (MRS-MPNNs). The authors prove that this approach ensures linearly independent node representations and empirically confirm that MRS-MPNNs prevent rank collapse and enhance the learning process.\

![](/images/uploads/2024/12/hero_log-1024x340.jpg)

The ability of message-passing neural networks (MPNNs) to fit complex functions over graphs is limited as most graph convolutions amplify the same signal across all feature channels, a phenomenon known as rank collapse, and over-smoothing as a special case. Most approaches to mitigate over-smoothing extend common message-passing schemes, e.g., the graph convolutional network, by utilizing residual connections, gating mechanisms, normalization, or regularization techniques. Our work contrarily proposes to directly tackle the cause of this issue by modifying the message-passing scheme and exchanging different types of messages using multi-relational graphs. We identify a sufficient condition to ensure linearly independent node representations. As one instantion, we show that operating on multiple directed acyclic graphs always satisfies our condition and propose to obtain these by defining a strict partial ordering of the nodes. We conduct comprehensive experiments that confirm the benefits of operating on multi-relational graphs to achieve more informative node representations.

Authors: *[Andreas Roth](https://www-ai.cs.tu-dortmund.de/PERSONAL/roth.html), [Franka Bause](/franka-bause/), [Nils Morten Kriege](/nils-kriege/), [Thomas Liebig](https://www-ai.cs.tu-dortmund.de/PERSONAL/liebig.html)*
