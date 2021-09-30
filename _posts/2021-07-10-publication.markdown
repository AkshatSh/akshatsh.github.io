---
layout: default
category: Publication
title: Assessing Data Efficiency in Task-Oriented Semantic Parsing
keywords: Data Efficiency, Semantic Parsing, Conversational AI
description: |
---

**Authors:** Shrey Desai, **Akshat Shrivastava**, Justin Rill, Brian Moran, Safiyyah Saleem, Alexander Zotov, and Ahmed Aly

Data efficiency, despite being an attractive characteristic, is often challenging to measure and optimize for in task-oriented semantic parsing; unlike exact match, it can require both modeland domain-specific setups, which have, historically, varied widely across experiments. In our work, as a step towards providing a unified solution to data-efficiencyrelated questions, we introduce a four-stage protocol which gives an approximate measure of how much in-domain, “target” data a parser requires to achieve a certain quality bar. Specifically, our protocol consists of (1) sampling target subsets of different cardinalities, (2) fine-tuning parsers on each subset, (3) obtaining a smooth curve relating target subset (%) vs. exact match (%), and (4) referencing the curve to mine ad-hoc (target subset, exact match) points. We apply our protocol in two real-world case studies—model generalizability and intent complexity—illustrating its flexiblity and applicability to practitioners in taskoriented semantic parsing.
[Arxiv Link](https://arxiv.org/abs/2107.04736)
