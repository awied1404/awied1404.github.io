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
citation: 'Christian Jaumann, Andreas Wiedholz, and Annemarie Friedrich. 2025. LGAR: Zero-Shot LLM-Guided Neural Ranking for Abstract Screening in Systematic Literature Reviews. In Findings of the Association for Computational Linguistics: ACL 2025, pages 7910–7927, Vienna, Austria. Association for Computational Linguistics.'
---
The scientific literature is growing rapidly, making it hard to keep track of the state-of-the-art. Systematic literature reviews (SLRs) aim to identify and evaluate all relevant papers on a topic. After retrieving a set of candidate papers, the abstract screening phase determines initial relevance. To date, abstract screening methods using large language models (LLMs) focus on binary classification settings; existing question answering (QA) based ranking approaches suffer from error propagation. LLMs offer a unique opportunity to evaluate the SLR’s inclusion and exclusion criteria, yet, existing benchmarks do not provide them exhaustively. We manually extract these criteria as well as research questions for 57 SLRs, mostly in the medical domain, enabling principled comparisons between approaches. Moreover, we propose LGAR, a zero-shot LLM Guided Abstract Ranker composed of an LLM based graded relevance scorer and a dense re-ranker. Our extensive experiments show that LGAR outperforms existing QA-based methods by 5-10 pp. in mean average precision. Our code and data is publicly available.
