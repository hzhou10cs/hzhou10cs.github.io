---
title:          "Fairness-Oracular MARL with Competitor-Aware Signals for Collaborative Inference"
date:           2025-09-10 00:01:00 +0800
selected:       true
pub:            "NeurIPS '25 - AI4NextG: The Thirty-Ninth Annual Conference on Neural Information Processing Systems"
# pub_date:       "2025"
abstract: >-
  Collaborative inference (CI) in NextG networks enables battery-powered devices to collaborate with nearby edges on deep learning inference. The fairness issue in a multi-device multi-edge (M2M) CI system remains underexplored. Mean-field multi-agent reinforcement learning (MFRL) is a promising solution for its low complexity and adaptability to system dynamics. However, the mobility nature in M2M CI systems hinders their effectiveness, as it breaks the premise of stable mean-field statistics. We propose FOCI (Fairness-Oriented Collaborative Inference), an RL-based method with two components: (i) an oracle-shaping reward for approaching max-min fairness, and (ii) a competitor-aware observation augmentation for stabilizing device behaviors. We provide a convergence guarantee with bounded estimation errors. According to the results from real-world devices mobility traces, FOCI shows the best performance on multiple metrics and tightens the tails. It reduces worst-case latency by up to 56\% and worst-case energy by 46\% versus baselines, while halving the switch cost and preserving competitive QoS.
cover:          /assets/images/covers/2025NERUIPS.jpg
authors:
- <strong>Hansong Zhou</strong>
- Xiaonan Zhang
# links:
#   Paper: https://ieeexplore.ieee.org/abstract/document/11044586
---