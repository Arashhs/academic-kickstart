---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Dynamic Graphs from All Contextual Information for Accurate Point-of-Interest
  Visit Forecasting
subtitle: ''
summary: 'In this study, we address the challenge of accurately forecasting the number of visits to Points-of-Interest (POIs) in urban areas, with important implications for urban planning, public health, and social studies. Existing approaches often overlook the intricate multi-context correlations among POIs, limiting the accuracy of visit forecasting. To overcome this limitation, we propose the Busyness Graph Neural Network (BysGNN), a novel temporal graph neural network that effectively uncovers and learns the underlying multi-context correlations between POIs.


BysGNN takes advantage of all available contextual information, including POI geocoordinates, semantics, and time-series data, to construct a comprehensive and accurate dynamic graph representation. By generating a graph that captures correlations between POIs at various levels, BysGNN reveals latent relationships between POIs, enabling more precise forecasting. The inferred expressive graph, referred to as the Busyness Graph, is then utilized in a Graph Neural Network (GNN) block to perform accurate visit forecasting, leveraging the flexibility and power of GNNs.'
authors:
- Arash Hajisafi
- Haowen Lin
- Sina Shaham
- Haoji Hu
- Maria Despoina Siampou
- Yao-Yi Chiang
- Cyrus Shahabi
tags:
- Computer Science - Machine Learning
- Computer Science - Social and Information Networks
categories: []
date: '2023-06-01'
lastmod: 2023-08-09T20:05:30-07:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-08-10T03:05:29.560304Z'
publication_types:
- '0'
abstract: Forecasting the number of visits to Points-of-Interest (POI) in an urban
  area is critical for planning and decision-making for various application domains,
  from urban planning and transportation management to public health and social studies.
  Although this forecasting problem can be formulated as a multivariate time-series
  forecasting task, the current approaches cannot fully exploit the ever-changing
  multi-context correlations among POIs. Therefore, we propose Busyness Graph Neural
  Network (BysGNN), a temporal graph neural network designed to learn and uncover
  the underlying multi-context correlations between POIs for accurate visit forecasting.
  Unlike other approaches where only time-series data is used to learn a dynamic graph,
  BysGNN utilizes all contextual information and time-series data to learn an accurate
  dynamic graph representation. By incorporating all contextual, temporal, and spatial
  signals, we observe a significant improvement in our forecasting accuracy over state-of-the-art
  forecasting models in our experiments with real-world datasets across the United
  States.
publication: '*arXiv*'
doi: 10.48550/arXiv.2306.15927
links:
- name: URL
  url: http://arxiv.org/abs/2306.15927
---
