---
title:          "EvoRAG: Making KG-based RAG Automatically Evolve through Feedback Backpropagation"
date:           2026-10-30 00:01:00 +0800
selected:       true
pub:            "IEEE International Conference on Data Engineering"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2027"

abstract: >-
  In this work, we propose EvoRAG, a self-evolving KG-RAG framework that leverages the feedback over generated responses to continuously refine the KG and enhance reasoning accuracy. EvoRAG introduces a feedback backpropagation mechanism that attributes feedback to retrieved paths by measuring their utility for response and propagates this utility back to individual triplets, supporting fine-grained KG refinements towards more adaptive and accurate reasoning. Through EvoRAG, we establish a closed loop that couples feedback, LLM, and graph data, continuously enhancing the performance and robustness in real-world scenarios. Experimental results show that EvoRAG improves reasoning accuracy by 7.34% over state-of-the-art KG-RAG frameworks.

cover:          /assets/images/covers/icde-evorag.png
authors:
  - "<b style='font-weight:900;color:#000;'>Zhenbo Fu</b>"
  - Yuanzhe Zhang
  - Qiange Wang
  - Hao Yuan
  - Yuehao Xu
  - Enze Yi
  - Yanfeng Zhang
  - Ge Yu
links:
  Paper: https://arxiv.org/abs/2604.15676v2
  Code: https://github.com/EvoRAG
---