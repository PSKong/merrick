---
title: "Controlled graph neural networks with denoising diffusion for anomaly detection."
collection: publications
category: manuscripts
permalink: /publication/2024-03-01-Controlled graph neural networks with denoising diffusion for anomaly detection
excerpt: 'Leveraging labels in a supervised learning framework as prior knowledge to enhance network anomaly detection has become a trend. Unfortunately, just a few labels are typically available due to the expensive labeling cost. The limited labeled data might not adequately represent the underlying distribution of the data, making the trained model fail to accurately detect anomalies in test data that fall outside the labeled data’s distribution. Recently, data augmentation has been widely used to address this issue. However, general graph data augmentation methods might lead to suboptimal performance when directly applying to network anomaly detection as they might alter graph semantics. In this paper, we provide a denoising diffusion probabilistic model (DDPM)-based Controlled Graph Neural Networks (ConGNN) that can address the problem of insufficient labeled data. In particular, we propose a graph-specific diffusion model-based generator which can inject the characteristics of a reference node into another source node. This generator is adopted to steer the procedure of neighborhood aggregation in GNN to build a controlled GNN for generating augmented data. Based on these augmented data, we present a data-enclosing hypersphere model with our designed consistency regularization term to perform anomaly detection. Extensive experiments demonstrate the superior performance of our model compared to the state-of-the-art baselines.'
date: 2024-03-01
venue: 'Expert Systems with Applications'
slidesurl: ''
paperurl: 'https://doi.org/10.1016/j.eswa.2023.121533'
citation: 'Xuan Li, Chunjing Xiao, Ziliang Feng, Shikang Pang, Wenxin Tai, Fan Zhou. (2024). &quot;Controlled graph neural networks with denoising diffusion for anomaly detection.&quot; <i>Expert Systems with Applications</i>. 1(2).'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
