---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

For a full list, see my <a href="https://scholar.google.com/citations?user=no1iGv4AAAAJ&hl=en&oi=sra" target="_blank">Google Scholar</a>.

<div class="research-cards">
  <a href="#human-ai-teaming" class="research-card">
    <div class="card-icon">🤖</div>
    <div class="card-title">Human-AI Teaming</div>
    <div class="card-desc">How AI teammates enters groups and change group dynamics</div>
  </a>
  <a href="#collaboration-analytics" class="research-card">
    <div class="card-icon">🔗</div>
    <div class="card-title">Collaboration Analytics</div>
    <div class="card-desc">Using ML and NLP to understand and measure how people collaborate</div>
  </a>
  <a href="#algorithmic-fairness" class="research-card">
    <div class="card-icon">⚖️</div>
    <div class="card-title">Algorithmic Fairness</div>
    <div class="card-desc">Detecting and mitigating bias in educational algorithms, especially for marginalized learners.</div>
  </a>
  <a href="#educational-data-science" class="research-card">
    <div class="card-icon">📊</div>
    <div class="card-title">Educational Data Science</div>
    <div class="card-desc">Using ML and NLP to understand and improve learning outcomes.</div>
  </a>
</div>

<style>
.research-cards {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
  margin: 2rem 0 3rem 0;
}
.research-card {
  display: block;
  padding: 1.6rem 1.75rem;
  border: 1.5px solid #e2e8f0;
  border-radius: 12px;
  text-decoration: none;
  color: inherit;
  transition: border-color 0.2s, box-shadow 0.2s;
}
.research-card:hover {
  border-color: #b509ac;
  box-shadow: 0 2px 16px rgba(181, 9, 172, 0.1);
  text-decoration: none;
  color: inherit;
}
.card-icon { font-size: 2rem; margin-bottom: 0.6rem; }
.card-title { font-weight: 700; font-size: 1.15rem; margin-bottom: 0.4rem; color: #111827; }
.card-desc { font-size: 0.95rem; color: #4b5563; line-height: 1.5; }
@media (max-width: 600px) {
  .research-cards { grid-template-columns: 1fr; }
}
.section-pill {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  background: #fdf4ff;
  border-radius: 999px;
  padding: 0.4rem 1.1rem;
  font-size: 1rem;
  font-weight: 600;
  color: #1a202c;
  margin: 2.5rem 0 0.6rem 0;
  scroll-margin-top: 80px;
}
.section-desc {
  display: block;
  background: #f8fafc;
  border-radius: 12px;
  padding: 0.75rem 1.1rem;
  font-size: 0.95rem;
  color: #4b5563;
  line-height: 1.6;
  margin-bottom: 1rem;
}
</style>

<div class="section-pill" id="human-ai-teaming">🤖 Human-AI Teaming</div>
<div class="section-desc">AI is no longer just a tool now -- it can act as a teammate with sociocognitive and affective capabilities. I study how AI teammates reshape group dynamics and knowledge co-construction process, and design AI teammates that adapt to their teammates' group dynamics to be more socially responsive.</div>

<div class="publications">
{% bibliography --query @*[category~=human-ai-teaming] --group_by none %}
</div>

<div class="section-pill" id="collaboration-analytics">🔗 Collaboration Analytics</div>
<div class="section-desc">Collaboration is central to how we learn—and I use machine learning and natural language processing to understand collaborative dynamics. Specifically, I develop Inclusion Analytics, an NLP method to measure how inclusion manifests through participation equity, epistemic dynamics, and sense of belonging in collaborative discourse.</div>

<div class="publications">
{% bibliography --query @*[category~=collaboration-analytics] --group_by none %}
</div>

<div class="section-pill" id="algorithmic-fairness">⚖️ Algorithmic Fairness</div>
<div class="section-desc">Algorithms in education are not value-neutral. I examine how biases emerge in educational algorithms — especially for minority and marginalized groups — and develop strategies to reliably measure and mitigate them.</div>

<div class="publications">
{% bibliography --query @*[category~=algorithmic-fairness] --group_by none %}
</div>

<div class="section-pill" id="educational-data-science">📊 Educational Data Science</div>
<div class="section-desc">I use Machine Learning and Natural Language Processing to understand how we learn, and develop computational methods to improve learning outcomes.</div>

<div class="publications">
{% bibliography --query @*[category~=educational-data-science] --group_by none %}
</div>
