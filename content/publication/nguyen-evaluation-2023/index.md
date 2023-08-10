---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Evaluation of Time-Series Anomaly Detection in Computer Networks
subtitle: ''
summary: ''
authors:
- Hong Nguyen
- Arash Hajisafi
- Alireza Abdoli
- Seon Ho Kim
- Cyrus Shahabi
tags:
- Anomaly Detection
- Computational modeling
- Computer networks
- Computer Networks
- Data models
- Deep learning
- Deep Learning
- Detectors
- Labeling
- Time series analysis
- Time-series Data Analysis
- Unsupervised Learning
categories: []
date: '2023-01-01'
lastmod: 2023-08-09T20:05:29-07:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-08-10T03:05:28.938208Z'
publication_types:
- '1'
abstract: One critical issue in any network systems is failure detection. Failures
  not only impact the source network but also propagate through other communicating
  networks due to the butterfly effect, making root causing of failures even more
  challenging. Therefore, the necessity to detect failures and anomalies in computer
  networks is fundamental. Given the nature of computer networks, data is received
  in a time-series format where each time-point has temporal dependencies on others.
  As a result, time-series analysis stands out as a potential approach to deal with
  the task of network anomaly detection. In this paper, we conduct studies on multivariate
  time series anomaly detection, varying from traditional machine learning techniques
  to deep learning models. We show that the choice of models is not as important as
  the choice of pre-processing techniques. Interestingly, non-linear normalization
  can boost the performance of deep detectors by around 20% in terms of F1 score and
  balance the preference of deep detectors for specific types of anomalies. We also
  study the bias of anomaly types to deep detectors, time-performance trade-offs,
  shortage of data, and effects of weakly labeled data on both synthetic and realworld
  datasets to fill out the missing insights in the literature.
publication: '*2023 International Conference on Information Networking (ICOIN)*'
doi: 10.1109/ICOIN56518.2023.10049051
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10049051
---
