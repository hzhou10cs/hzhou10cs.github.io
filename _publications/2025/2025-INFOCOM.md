---
title:          "Similarity-Guided Rapid Deployment of Federated Intelligence Over Heterogeneous Edge Computing"
date:           2025-05-19 00:01:00 +0800
selected:       true
pub:            "INFOCOM '25: IEEE Conference on Computer Communications"
# pub_date:       "2025"
abstract: >-
  Edge computing is envisioned to enable rapid federated intelligence on edge devices to satisfy their dynamically changing AI service demands. Semi-Asynchronous FL (Semi-Async FL) enables distributed learning in an asynchronous manner, where the server does not have to wait all local models for improving the global model. Hence, it takes a small time to well-train a global model. However, system heterogeneity in edge computing results in staleness issue, which will deteriorate training accuracy. In this paper, we propose to accelerate Semi-Async FL while ensuring training accuracy by designing a Similarity-Aware Aggregation (SAA) strategy. SAA is able to enhance the aggregation quality and thus decrease the wall-clock time, the training time for a certain accuracy. Particularly, we leverage the global model similarity to describe the local model influence and let those with higher influence contribute more to global aggregation. We further measure the similarity between global model update deviations as directional similarity, which is then used for determining aggregation timing. We theoretically provide a convergence analysis to SAA. Our extensive experimental results empirically show that the proposed SAA strategy reduces up to 53.7% wall-clock time and 59.4% wall-clock round for Semi-Async FL compared with several benchmark schemes.
cover:          /assets/images/covers/2025INFOCOM.jpg
authors:
- <strong>Hansong Zhou</strong>
- Jingjing Fu
- Yukun Yuan
- Linke Guo
- Xiaonan Zhang
links:
  Paper: https://ieeexplore.ieee.org/abstract/document/11044586
---