---
title: "AI Agent for Rural Health"
group: "Demo"
show: true
width: 12           # 12 = full row, 6 = half, etc.
date: 2025-02-02
---

<div class="project-card">
  <div class="project-card-top">
    <!-- left: cover image -->
    <div class="project-cover">
      <img src="/assets/images/covers/RuralAI_Cover.jpg" alt="Edge LLM Demo">
    </div>


<!-- right: intro -->
<div class="project-intro">
    <h2 class="h5 mb-2">AI Agent for Rural Health</h2>
    <p>
    To improve health outcomes in remote areas with scarce medical resources, we are developing an AI assistant dedicated to supporting behavior change and enhancing patient health. We first built an end-to-end data pipeline that distilled ~2,000 hours of weight-loss consultations into a clean, consistent training JSON data. The process emphasized privacy, conversation quality, and coherent session structure, producing a domain-specific dataset ready for fine-tuning a specialized coaching agent.
    </p>
    <p>
    At inference time, we use few-shot prompt engineering and a lightweight knowledge graph to ground responses. Curated exemplars model tone and behavior-change steps, while the graph links goals, habits, and constraints so the agent retrieves relevant guidance and stays consistent across scenarios.
    </p>
    <p>
    To preserve long-term memory and explainability, we designed a dual-agent loop: a coach that speaks briefly and a structured extractor that writes validated deltas to a shared state for follow-ups across weeks. This architecture stabilizes context, reduces drift, and supports population-level insights later.
    </p>
    <ul class="mb-0 small text-muted">
    <li>Base model (prototype): Qwen-3-4B</li>
    <li>Fine-tuning dataset: 2000 hrs of weight-losing consultations</li>
    </ul>
</div>
</div>

  <div class="project-card-video">
    <!-- YouTube embed -->
    <div class="embed-responsive embed-responsive-16by9">
    </div>

    <!-- Or self-hosted video instead of YouTube:
    <video controls class="w-100 h-100">
      <source src="/assets/videos/edge-llm-demo.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    -->
  </div>
</div>
