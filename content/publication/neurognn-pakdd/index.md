---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dynamic GNNs for Precise Seizure Detection and Classification from EEG Data
subtitle: ''
summary: ''
authors:
- Arash Hajisafi
- Haowen Lin
- Yao-Yi Chiang
- Cyrus Shahabi

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''

tags:
- Computer Science - Machine Learning
categories: []
date: '2024-01-28'
lastmod: 2024-01-28T20:05:30-07:00
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
publishDate: '2024-01-28T03:05:30.147875Z'
publication_types:
- '0'
abstract: Diagnosing epilepsy requires accurate seizure detection and classification, but traditional manual EEG signal analysis is resourceintensive. Meanwhile, automated algorithms often overlook EEG’s geometric and semantic properties critical for interpreting brain activity. This paper introduces NeuroGNN, a dynamic Graph Neural Network (GNN) framework that captures the dynamic interplay between the EEG electrode locations and the semantics of their corresponding brain regions. The specific brain region where an electrode is placed critically shapes the nature of captured EEG signals. Each brain region governs distinct cognitive functions, emotions, and sensory processing, influencing both the semantic and spatial relationships within the EEG data. Understanding and modeling these intricate brain relationships are essential for accurate and meaningful insights into brain activity. This is precisely where the proposed NeuroGNN framework excels by dynamically constructing a graph that encapsulates these evolving spatial, temporal, semantic, and taxonomic correlations to improve precision in seizure detection and classification. Our extensive experiments with real-world data demonstrate that NeuroGNN significantly outperforms existing state-ofthe-art models.
publication: "*PAKDD '24*"
doi: ''
# links:
# - name: URL
#   url: http://arxiv.org/abs/2307.15838
---