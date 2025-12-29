---
title: "On dyadic fairness: Exploring and mitigating bias in graph connections."
authors:
  - Peizhao Li
  - me
  - Han Zhao
  - Pengyu Hong
  - Hongfu Liu
# author_notes:
#   - Equal contribution
#   - Equal contribution
date: "2021-01-12T00:00:00Z"
publishDate: "2021-01-12T00:00:00Z"
publication_types:
  - paper-conference
publication: In *International Conference on Learning Representations*
publication_short: In *ICLR*
abstract: Disparate impact has raised serious concerns in machine learning applications and its societal impacts. In response to the need of mitigating discrimination, fairness has been regarded as a crucial property in algorithmic designs. In this work, we study the problem of disparate impact on graph-structured data. Specifically, we focus on dyadic fairness, which articulates a fairness concept that a predictive relationship between two instances should be independent of the sensitive attributes. Based on this, we theoretically relate the graph connections to dyadic fairness on link predictive scores in learning graph neural networks, and reveal that regulating weights on existing edges in a graph contributes to dyadic fairness conditionally. Subsequently, we propose our algorithm, FairAdj, to empirically learn a fair adjacency matrix with proper graph structural constraints for fair link prediction, and in the meanwhile preserve predictive accuracy as much as possible. Empirical validation demonstrates that our method delivers effective dyadic fairness in terms of various statistics, and at the same time enjoys a favorable fairness-utility tradeoff.
summary: We theoretically relate the graph connections to dyadic fairness on link predictive scores in learning graph neural networks and accordingly introduced an algorithm for fair link prediction by adjusting the adjacency weight matrix to address the fairness-utility trade-off.
tags:
  - Graph Neural Network
  - Fairness
featured: true
hugoblox: []
links:
  - "type: pdf"
  - "type: code"
  - "type: dataset"
  - "type: source"
  - "type: video"
image: []
projects:
  - example
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
