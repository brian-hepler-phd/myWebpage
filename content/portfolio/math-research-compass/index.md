---
title: MathResearchCompass
date: 2025-04-10
external_link: https://github.com/brian-hepler-phd/MathResearchCompass
tags:
  - Topic Modeling
  - arXiv
  - NLP
  - BERTopic
  - Research Tools
  - In Progress
---

An in-progress dashboard for visualizing mathematical research trends across the arXiv. This project uses topic modeling, NLP, and arXiv metadata to map collaborations and thematic structure within the mathematical sciences.

<!--more-->

The goal is to identify:

- Emerging topics across subfields (e.g. algebraic geometry, representation theory)
- Key research clusters and coauthor networks
- Thematic overlaps between adjacent arXiv categories (e.g. math.AG and math.RT)

The current pipeline uses:

- `BERTopic` with sentence-transformer embeddings
- Dimensionality reduction via UMAP
- Clustering with HDBSCAN
- Metadata aggregation from arXiv API
- Interactive visualizations powered by Plotly and Pandas

Planned features include:

- Implement collaboration network analysis and visualization
- Incorporate citation data (if accessible) for impact analysis

 GitHub:  
 [MathResearchCompass](https://github.com/brian-hepler-phd/MathResearchCompass)