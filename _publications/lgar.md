---
title: "LGAR: Zero-Shot LLM-Guided Neural Ranking for Abstract Screening in Systematic Literature Reviews"
collection: publications
category: conferences
permalink: /publication/lgar
excerpt: 'In this work an approach using LLM to rank papers for relevance to a research question for Systematic Literature Reviews is presented.'
date: 2025-07-31
venue: 'ACL Findings'
bibtexurl: 'http://awied1404.github.io/files/lgar.bib'
paperurl: 'http://awied1404.github.io/files/lgar.pdf'
citation: 'Wiedholz, A., Heider, M., Nordsieck, R., Angerer, A., Dietrich, S. and Hähner, J. (2021). CAD-based Grasp and Motion Planning for Process Automation in Fused Deposition Modelling. In Proceedings of the 18th International Conference on Informatics in Control, Automation and Robotics - ICINCO; ISBN 978-989-758-522-7; ISSN 2184-2809, SciTePress, pages 450-458. DOI: 10.5220/0010571204500458'
---
The scientific literature is growing rapidly, making it hard to keep track of the state-of-the-art. Systematic literature reviews (SLRs) aim to identify and evaluate all relevant papers on a topic. After retrieving a set of candidate papers, the abstract screening phase determines initial relevance. To date, abstract screening methods using large language models (LLMs) focus on binary classification settings; existing question answering (QA) based ranking approaches suffer from error propagation. LLMs offer a unique opportunity to evaluate the SLR’s inclusion and exclusion criteria, yet, existing benchmarks do not provide them exhaustively. We manually extract these criteria as well as research questions for 57 SLRs, mostly in the medical domain, enabling principled comparisons between approaches. Moreover, we propose LGAR, a zero-shot LLM Guided Abstract Ranker composed of an LLM based graded relevance scorer and a dense re-ranker. Our extensive experiments show that LGAR outperforms existing QA-based methods by 5-10 pp. in mean average precision. Our code and data is publicly available.
