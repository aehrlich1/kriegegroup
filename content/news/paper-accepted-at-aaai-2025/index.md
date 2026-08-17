---
title: "Paper Accepted at AAAI 2025"
url: "/paper-accepted-at-aaai-2025/"
date: 2024-12-11T15:25:39
author: "Lorenz Kummer"
summary: "We are excited to announce the acceptance of our recent work “Crossfire: An Elastic Defense Framework for Graph Neural Networks under Bit Flip Attacks” by Lorenz Kummer, Samir Moustafa, Wilfried Gansterer and Nils Kriege at the 39th Annual AAAI Conference on Artificial Intelligence, which will take place in Philadelphia, Pennsylvania, USA from February 25 – […]"
image: "/images/news/aaai-2025-paper.png"
---

We are excited to announce the acceptance of our recent work “Crossfire: An Elastic Defense Framework for Graph Neural Networks under Bit Flip Attacks” by *Lorenz Kummer, Samir Moustafa, Wilfried Gansterer* and *Nils Kriege* at the 39th Annual AAAI Conference on Artificial Intelligence, which will take place in Philadelphia, Pennsylvania, USA from February 25 – March 4, 2025!

Graph Neural Networks (GNNs) play a crucial role in fields like medicine, finance, and drug discovery, yet, as we discovered in our 2024 KDD paper “[Attacking Graph Neural Networks with Bit Flips: Weisfeiler and Leman Go Indifferent](https://dl.acm.org/doi/10.1145/3637528.3671890)“, they are vulnerable to certain Bit Flip Attacks (BFAs), which manipulate model weights to degrade performance. This vulnerability of GNNs and, more importantly, techniques to mitigate it, are a severely underexplored research domain. To address this, we have developed Crossfire, the first retraining-free defense framework tailored to safeguard GNNs from BFAs.

Crossfire combines innovative techniques like saliency-based honeypot neuron induction, the exploitation of sparsity, and cryptographic hashing to detect and repair compromised weights efficiently on the bit-level. It achieves near-perfect attack detection and restores models to their pre-attack state with significantly higher accuracy and reliability than existing defenses ported from the computer vision domain.

Tested across six datasets and over 2,000 experiments, Crossfire improves reconstruction probabilities by 21.8% and post-repair prediction quality by 10.85% compared to competitors. Despite its robust capabilities, the framework introduces minimal computational and storage overhead, making it a scalable solution for real-world deployment.

With its groundbreaking hybrid approach, Crossfire fills a critical gap in GNN security, offering researchers and practitioners a powerful tool to defend against adversarial attacks.

Authors: *[Lorenz Kummer](/lorenz-kummer/), [Samir Moustafa](https://taa.cs.univie.ac.at/team/person/117244/), [Wilfried Gansterer](https://ufind.univie.ac.at/de/person.html?id=82687), [Nils Kriege](/nils-kriege/)*
