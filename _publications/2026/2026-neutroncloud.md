---
title:          "NeutronCloud: Resource-Aware Distributed GNN Training in Fluctuating Cloud Environments"
date:           2026-02-01 00:01:00 +0800
selected:       false
pub:            "Very Large Data Bases (VLDB)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  In this paper, we propose NeutronCloud, a system designed for efficient GNN training in cloud environments. First, we adopt a resource-aware workload adjustment strategy. It builds on hybrid dependency handling by obtaining dependency information through both local computation and remote communication. During training, it dynamically adjusts the ratio between locally computed and remotely fetched dependencies based on each worker's available resources, ensuring workload-resource alignment. Second, we employ a dependency-aware partial-reduce approach reusing historical vertex embeddings and skipping the stragglers during gradient aggregation to address extreme resource fluctuations that cause some workers to lag significantly behind others in the cluster. 
cover:          /assets/images/covers/vldb-neutroncloud.png
authors:
  - Mingyi Cao
  - Chunyu Cao
  - Yanfeng Zhang
  - "<b style='font-weight:900;color:#000;'>Zhenbo Fu</b>"
  - Xin Ai
  - Qiange Wang
  - Yu Gu
  - Ge Yu
links:
---
