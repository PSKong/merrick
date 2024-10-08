---
title: "Counterfactual Data Augmentation With Denoising Diffusion for Graph Anomaly Detection"
collection: publications
category: manuscripts
permalink: /publication/2024-06-01-Counterfactual Data Augmentation With Denoising Diffusion for Graph Anomaly Detection
excerpt: 'A critical aspect of graph neural networks (GNNs) is to enhance the node representations by aggregating node neighborhood information. However, when detecting anomalies, the representations of abnormal nodes are prone to be averaged by normal neighbors, making the learned anomaly representations less distinguishable. To tackle this issue, we propose an unsupervised counterfactual data augmentation method for graph anomaly detection (CAGAD) that introduces a graph pointer neural network as the heterophilic node detector to identify potential anomalies whose neighborhoods are normal-node-dominant. For each identified potential anomaly, we design a graph-specific diffusion model to translate a part of its neighbors, which are probably normal, into anomalous ones. At last, we involve these translated neighbors in GNN neighborhood aggregation to produce counterfactual representations of anomalies. Through aggregating the translated anomalous neighbors, counterfactual representations become more distinguishable and further advocate detection performance. The experimental results on four datasets demonstrate that CAGAD significantly outperforms strong baselines, with an average improvement of 2.35% on F1, 2.53% on AUC-ROC, and 2.79% on AUC-PR.'
date: 2024-06-01
venue: 'IEEE Transactions on Computational Social Systems'
slidesurl: ''
paperurl: 'https://ieeexplore.ieee.org/document/10564850'
citation: 'Xiao, Chunjing and Pang, Shikang and Xu, Xovee and Li, Xuan and Trajcevski, Goce and Zhou, Fan. (2024). &quot;Counterfactual Data Augmentation With Denoising Diffusion for Graph Anomaly Detection.&quot; <i>Journal 1</i>. 1(3).'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
