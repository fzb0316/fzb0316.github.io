---
title:          "NeutronJittor: Efficient CPU-GPU Memory Management for GNN Training with Jittor"
date:           2026-10-03 00:01:00 +0800
selected:       true
pub:            "Fundamental Research"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  Full-graph GNN training often provides better accuracy and stability, but its large memory footprint and irregular graph access patterns make user-transparent memory management on GPUs inefficient. We propose NeutronJittor, a GNN training system that reduces redundant computation through embedding reuse across shared vertices within an epoch and lowers CPU–GPU data movement with a spatial–temporal-aware scheduler that keeps high-priority vertex data on the GPU.

cover:          /assets/images/covers/fr-neutronjittor.png
authors:
  - Shizhan Lu *
  - "<b style='font-weight:900;color:#000;'>Zhenbo Fu *</b>"
  - Qiange Wang
  - Yanfeng Zhang
  - Yuehao Xu
  - Xin Ai
  - Zhewei Wei
  - Ge Yu
links:
  Paper: https://www.sciencedirect.com/science/article/pii/S2667325826004541?ref=pdf_download&fr=RR-2&rr=a0ce6a0e7c6dd531
  Code: https://github.com/NeutronJittor
---