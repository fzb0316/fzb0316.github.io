---
title:          "DepCache: A KV Cache Management Framework for GraphRAG with Dependency Attention"
date:           2026-04-18 00:01:00 +0800
selected:       false
pub:            "Special Interest Group on Management of Data (SIGMOD)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  We introduce dependency attention, a novel graph-aware attention mechanism that restricts attention computation to token pairs with structural dependencies in the retrieved subgraph. Unlike standard self-attention that computes fully connected interactions, dependency attention prunes irrelevant token pairs and reuses computations along shared relational paths, substantially reducing inference overhead. Building on this idea, we develop DepCache, a KV cache management framework tailored for dependency attention. 

cover:          /assets/images/covers/sigmod-depcache.png
authors:
  - Hao Yuan
  - Xin Ai
  - Qiange Wang
  - Peizheng Li
  - Jiayang Yu
  - Chaoyi Chen
  - Xinbo Yang
  - Yanfeng Zhang
  - "<b style='font-weight:900;color:#000;'>Zhenbo Fu</b>"
  - Yingyou Wen
  - Ge Yu
links:
---
