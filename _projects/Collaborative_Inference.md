---
title: "Real-time Multi-edge Collaborative Inference System"
group: "Demo"
show: true
width: 12           # 12 = full row, 6 = half, etc.
date: 2025-10-01
---

<div class="project-card">
  <div class="project-card-top">
    <!-- left: cover image -->
    <div class="project-cover">
      <img src="/assets/images/covers/Collab_Cover.jpg" alt="Edge LLM Demo">
    </div>

<!-- right: intro -->
<div class="project-intro">
    <h2 class="h5 mb-2">Real-time Multi-edge Collaborative Inference System</h2>
    <p>
    For the vision of cooperative edge intelligence, this demo shows how idle or lightweight devices, such as intelligent assistant in smart home and idle AI edges developed in smart city, can pool their resources to serve modern large language models in real time.
    </p>
    <p>
    The system runs Meta Llama-3.2-3B-Instruct split across 3 NVIDIA Jetson Orin Nano boards, connected through a TP-Link 5-Port Gigabit unmanaged switch (other network fabrics or protocols could be used with the same design). 
    </p>
    <p>
    Under the hood, I first re-engineered Llama modeling components in HuggingFace Transformers to support the cross-device data pipeline. I then implemented a custom distributed inference engine in PyTorch compatible with the modified components to enable the real-time collaborative inference 
    </p>
    <ul class="mb-0 small text-muted">
    <li>Model: Llama-3.2-3B-Instruct, Full precision</li>
    <li>Device: Jetson Orin Nano</li>
    <li>Connection: TP-Link 5-Port Switch</li>
    </ul>
</div>
</div>

  <div class="project-card-video">
    <!-- YouTube embed -->
    <div class="embed-responsive embed-responsive-16by9">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/qGTWrGZsJak?si=QOL4yRtvj51yA2Go" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>

    <!-- Or self-hosted video instead of YouTube:
    <video controls class="w-100 h-100">
      <source src="/assets/videos/edge-llm-demo.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    -->
  </div>
</div>
