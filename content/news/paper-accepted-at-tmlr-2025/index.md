---
title: "Paper Accepted at TMLR 2025"
url: "/paper-accepted-at-tmlr-2025/"
date: 2025-01-08T08:24:35
author: "Franka Bause"
summary: "We are excited to announce that the paper Maximally Expressive GNNs for Outerplanar Graphs by Franka Bause, Fabian Jogl, Patrick Indri, Tamara Drucks, David Penz, Nils Kriege, Thomas Gärtner, Pascal Welke, and Maximilian Thiessen has been accepted to Transactions on Machine Learning Research (TMLR)! The paper proposes a linear time graph transformation that enables the […]"
image: "/images/uploads/2025/01/tmlr.png"
---

We are excited to announce that the paper *[Maximally Expressive GNNs for Outerplanar Graphs](https://openreview.net/pdf?id=XxbQAsxrRC)* by *[Franka Bause](/franka-bause/), [Fabian Jogl](https://informatics.tuwien.ac.at/people/fabian-jogl), [Patrick Indri](https://informatics.tuwien.ac.at/people/patrick-indri), [Tamara Drucks](https://informatics.tuwien.ac.at/people/tamara-drucks), [David Penz](https://informatics.tuwien.ac.at/people/david-penz), [Nils Kriege](/nils-kriege/), [Thomas Gärtner](https://informatics.tuwien.ac.at/people/thomas-gaertner), [Pascal Welke](https://informatics.tuwien.ac.at/people/pascal-welke),* and *[Maximilian Thiessen](https://informatics.tuwien.ac.at/people/maximilian-thiessen)* has been accepted to Transactions on Machine Learning Research ([TMLR](https://jmlr.org/tmlr/index.html))!

![Image show the CAT algorithm. On the left an image of a graph G, on the right the CAT transformed graph CAT(G).](/images/uploads/2025/01/cat.png)

The CAT graph transformation that enables message passing GNNs to distinguish all outerplanar graphs.

The paper proposes a linear time graph transformation that enables the Weisfeiler-Leman (WL) algorithm and message passing graph neural networks (MPNNs) to be maximally expressive on outerplanar graphs. Our approach is motivated by the fact that most pharmaceutical molecules correspond to outerplanar graphs. Existing research predominantly enhances the expressivity of graph neural networks without specific graph families in mind. This often leads to methods that are impractical due to their computational complexity. In contrast, the restriction to outerplanar graphs enables us to encode the Hamiltonian cycle of each biconnected component in linear time. As the main contribution of the paper we prove that our method achieves maximum expressivity on outerplanar graphs. Experiments confirm that our graph transformation improves the predictive performance of MPNNs on molecular benchmark datasets at negligible computational overhead.

Authors: *[Franka Bause](/franka-bause/), [Fabian Jogl](https://informatics.tuwien.ac.at/people/fabian-jogl), [Patrick Indri](https://informatics.tuwien.ac.at/people/patrick-indri), [Tamara Drucks](https://informatics.tuwien.ac.at/people/tamara-drucks), [David Penz](https://informatics.tuwien.ac.at/people/david-penz), [Nils Kriege](/nils-kriege/), [Thomas Gärtner](https://informatics.tuwien.ac.at/people/thomas-gaertner), [Pascal Welke](https://informatics.tuwien.ac.at/people/pascal-welke), [Maximilian Thiessen](https://informatics.tuwien.ac.at/people/maximilian-thiessen)*
