---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<style>
.section-card {
  background: #fff;
  border: 1px solid #e8ecf3;
  border-radius: 14px;
  padding: 20px 26px 22px 26px;
  margin-bottom: 26px;
  box-shadow: 0 2px 14px rgba(20, 40, 80, 0.05);
}
.section-card h1,
.section-card h2 {
  margin-top: 0;
  border-bottom: 1px solid #eef1f6;
  padding-bottom: 8px;
}
.about-body {
  text-align: justify;
  line-height: 1.65;
}
.research-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem 0.6rem;
}
.research-tag {
  display: inline-block;
  padding: 0.32rem 0.75rem;
  background: #fff;
  border: 1px solid #d8e3fb;
  border-radius: 999px;
  font-size: 0.9em;
  font-weight: 600;
  color: #1a4f9c;
  white-space: nowrap;
}
</style>

<div class="section-card" style="margin-top: 24px;" markdown="1">
<h2>About Me</h2>
<div class="about-body">
I am a Ph.D. student (Sep. 2022 &ndash; present) at the <a href="https://english.nudt.edu.cn/">National University of Defense Technology</a> (NUDT), jointly trained with the <strong>Intelligent Game and Decision Lab</strong> (IGDL), where I am fortunate to work with Prof. <a href="https://qingyonghu.github.io/">Qingyong Hu</a>. I received my Bachelor's degree from NUDT in 2022. My work is on <strong>large language models</strong> and their <strong>post-training</strong>.
<br><br>
My research is about making large models more <strong>efficient</strong> and more <strong>reliable</strong>: which data is worth fine-tuning on, why reinforcement learning for reasoning collapses and how to fix it, how to tell when a model is hallucinating, and how well multimodal models actually reason rather than pattern-match. Recently I have been especially interested in <strong>distillation and multi-teacher supervision</strong> for multi-domain LLMs.
<br><br>
I am always glad to talk about research or collaboration &mdash; feel free to reach out by <a href="mailto:hexixiang@nudt.edu.cn">email</a>.
</div>

<div style="margin-top: 18px; background: #f4f7ff; border: 1px solid #d8e3fb; border-radius: 12px; padding: 14px 18px;">
  <div style="font-size: 0.82em; font-weight: 700; color: #1a73e8; text-transform: uppercase; letter-spacing: 0.6px; margin-bottom: 10px;">Research Interests</div>
  <div class="research-tags">
    <span class="research-tag">📊 Data-Centric Post-Training</span>
    <span class="research-tag">🎯 RL for LLM Reasoning</span>
    <span class="research-tag">🧪 Knowledge Distillation</span>
    <span class="research-tag">🔍 Trustworthy LLMs</span>
    <span class="research-tag">👁️ Multimodal Reasoning</span>
  </div>
</div>

</div>

<div class="section-card" markdown="1">

# 🔥 News

<ul style="margin:0; padding-left:1.2em;">
  <li><p style='text-align:justify; margin:4px 0'><i>2026.09</i>: &nbsp;🔥🔥 <strong>MT-SDPO</strong> is released on <a href="https://arxiv.org/abs/2609.02548">arXiv</a>, together with the SciKnowEval-L3 data, training code and evaluation protocol.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2026.05</i>: &nbsp;🔥🔥 <strong>StemBind</strong> is released on <a href="https://arxiv.org/abs/2606.00148">arXiv</a>, with a <a href="https://hexixiang.github.io/StemBind/">project page</a> and public leaderboard.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2026.05</i>: &nbsp;🎉🎉 <strong>AVSPO</strong> is accepted by <span style="color:#c0392b; font-weight:600;">ICML 2026</span>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2026.04</i>: &nbsp;🎉🎉 <strong>CALRD</strong> is accepted by <span style="color:#c0392b; font-weight:600;">IJCAI-ECAI 2026</span>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2026.02</i>: &nbsp;🎉🎉 <strong>ENC-Bench</strong> is accepted by <span style="color:#c0392b; font-weight:600;">CVPR 2026</span> as a <strong>Highlight</strong>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2025.11</i>: &nbsp;🎉🎉 <strong>Efficient Hallucination Detection</strong> is accepted by <span style="color:#c0392b; font-weight:600;">AAAI 2026</span> as an <strong>Oral</strong>.</p></li>
  <li><p style='text-align:justify; margin:4px 0'><i>2025.03</i>: &nbsp;🎉🎉 <strong>TACOS</strong> is accepted by <span style="color:#c0392b; font-weight:600;">ICME 2025</span>.</p></li>
</ul>

</div>

<div class="section-card" markdown="1">

# 📝 Publications

<div style="font-size: 0.92em; color: #666; margin-bottom: 2px;">
<sup>*</sup> denotes the corresponding author. Full list on <a href="https://scholar.google.com/citations?user=724HNF4AAAAJ&hl=en">Google Scholar</a>.
</div>

<style>
.publication-list { margin: 8px 0 0 0; padding: 0; list-style: none; }
.publication-item { border-bottom: 1px solid #efefef; padding: 18px 0; }
.publication-item:first-child { padding-top: 10px; }
.publication-item:last-child { border-bottom: none; }
.pub-title { font-size: 1.04em; font-weight: 700; line-height: 1.35; }
.pub-title a { color: #00369f; }
.pub-authors { margin-top: 6px; color: #333; line-height: 1.45; }
.pub-venue { margin-top: 6px; color: #666; line-height: 1.4; }
.pub-badge {
  display: inline-block; margin-right: 8px; padding: 2px 8px; border-radius: 4px;
  background: #eef4ff; color: #00369f; font-size: 0.82em; font-weight: 700; white-space: nowrap;
}
.pub-badge.pub-badge-preprint { background: #f3f3f5; color: #555; }
.pub-links { margin-top: 6px; font-size: 0.9em; }
.pub-links a {
  display: inline-block; margin-right: 10px; padding: 1px 9px;
  border: 1px solid #d8e3fb; border-radius: 999px; color: #1a4f9c; text-decoration: none;
}
</style>

<ol class="publication-list">
  <li class="publication-item">
    <div class="pub-title"><a href="https://arxiv.org/abs/2609.02548">Learn from Whoever Is Right: Answer-Verified Multi-Teacher Distillation for Multi-Domain LLMs</a></div>
    <div class="pub-authors"><strong><u>Xixiang He</u></strong>, Xingming Li, Baiqi Wu, Qiyao Sun, Xuanyu Ji, Ao Cheng, Qingyong Hu<sup>*</sup></div>
    <div class="pub-venue"><span class="pub-badge pub-badge-preprint">Preprint</span> arXiv preprint arXiv:2609.02548, 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2609.02548">arXiv</a><a href="https://github.com/hexixiang/MT-SDPO">Code</a></div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://arxiv.org/abs/2606.00148">StemBind: When MLLMs Get Lost Between Rules and Instances in Abstract Visual Reasoning</a></div>
    <div class="pub-authors"><strong><u>Xixiang He</u></strong>, Baiqi Wu, Xingming Li, Ao Cheng, Qiyao Sun, Xuanyu Ji, Qingyong Hu<sup>*</sup></div>
    <div class="pub-venue"><span class="pub-badge pub-badge-preprint">Preprint</span> arXiv preprint arXiv:2606.00148, 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2606.00148">arXiv</a><a href="https://hexixiang.github.io/StemBind/">Project Page</a></div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://arxiv.org/abs/2605.21125">Advantage Collapse in Group Relative Policy Optimization: Diagnosis and Mitigation</a></div>
    <div class="pub-authors"><strong><u>Xixiang He</u></strong>, Qiyao Sun, Ao Cheng, Xingming Li, Xuanyu Ji, Hailun Lu, Runke Huang, Qingyong Hu<sup>*</sup></div>
    <div class="pub-venue"><span class="pub-badge">ICML 2026</span> International Conference on Machine Learning, 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2605.21125">arXiv</a></div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://arxiv.org/abs/2507.03673">TACOS: Open Tagging and Comparative Scoring for Instruction Fine-Tuning Data Selection</a></div>
    <div class="pub-authors"><strong><u>Xixiang He</u></strong>, Hao Yu, Qiyao Sun, Ao Cheng, Tailai Zhang, Cong Liu, Shuxuan Guo<sup>*</sup></div>
    <div class="pub-venue"><span class="pub-badge">ICME 2025</span> IEEE International Conference on Multimedia and Expo, 2025</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2507.03673">arXiv</a></div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://arxiv.org/abs/2603.22763">ENC-Bench: A Benchmark for Evaluating Multimodal Large Language Models in Electronic Navigational Chart Understanding</a></div>
    <div class="pub-authors">Ao Cheng, Xingming Li, Xuanyu Ji, <strong><u>Xixiang He</u></strong>, Qiyao Sun, Chunping Qiu, Runke Huang, Qingyong Hu<sup>*</sup></div>
    <div class="pub-venue"><span class="pub-badge">CVPR 2026 Highlight</span> IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2603.22763">arXiv</a><a href="https://github.com/QingyongHu/ENC-Bench">Code</a></div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://arxiv.org/abs/2603.22812">Efficient Hallucination Detection: Adaptive Bayesian Estimation of Semantic Entropy with Guided Semantic Exploration</a></div>
    <div class="pub-authors">Qiyao Sun, Xingming Li, <strong><u>Xixiang He</u></strong>, Ao Cheng, Xuanyu Ji, Hailun Lu, Runke Huang, Qingyong Hu<sup>*</sup></div>
    <div class="pub-venue"><span class="pub-badge">AAAI 2026 Oral</span> AAAI Conference on Artificial Intelligence, 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2603.22812">arXiv</a></div>
  </li>
  <li class="publication-item">
    <div class="pub-title"><a href="https://qingyonghu.github.io/CALRD/">MLLMs Get It Right, Then Get It Wrong: Tracing and Correcting Late-Layer Textual Bias</a></div>
    <div class="pub-authors">Xingming Li, Ao Cheng, Qiyao Sun, <strong><u>Xixiang He</u></strong>, Xuanyu Ji, Runke Huang, Qingyong Hu<sup>*</sup></div>
    <div class="pub-venue"><span class="pub-badge">IJCAI-ECAI 2026</span> International Joint Conference on Artificial Intelligence, 2026</div>
    <div class="pub-links"><a href="https://qingyonghu.github.io/CALRD/">Project Page</a></div>
  </li>
</ol>

</div>

<style>
.timeline { position: relative; padding: 0; list-style: none; margin: 16px 0 0 0; }
.timeline::before {
  content: ''; position: absolute; left: 7px; top: 6px; bottom: 6px; width: 2px;
  background: linear-gradient(to bottom, #1a73e8 0%, #c5d8fb 100%); border-radius: 2px;
}
.timeline li { position: relative; padding: 0 0 22px 32px; margin: 0; font-size: 1em; }
.timeline li:last-child { padding-bottom: 4px; }
.timeline li::before {
  content: ''; position: absolute; left: 0; top: 6px; width: 16px; height: 16px; border-radius: 50%;
  background: #fff; border: 2.5px solid #1a73e8; box-shadow: 0 0 0 3px rgba(26,115,232,0.12); z-index: 1;
}
.timeline li.tl-current::before { background: #1a73e8; box-shadow: 0 0 0 4px rgba(26,115,232,0.18); }
.tl-period {
  display: inline-block; font-size: 0.78em; font-weight: 600; color: #1a73e8;
  background: rgba(26,115,232,0.08); border-radius: 4px; padding: 1px 8px;
  margin-bottom: 3px; letter-spacing: 0.2px;
}
.tl-period.tl-now { background: rgba(26,115,232,0.15); }
.tl-body { color: #333; margin-top: 2px; line-height: 1.5; }
.tl-body a { color: #1a73e8; }
.tl-sub { color: #888; font-size: 0.88em; margin-top: 1px; }
</style>

<div class="section-card" markdown="1">

# 📖 Educations

<ul class="timeline">
  <li class="tl-current">
    <span class="tl-period tl-now">2022.09 — Present</span>
    <div class="tl-body">Ph.D. Student · Large Language Models &amp; Post-training</div>
    <div class="tl-sub"><a href="https://english.nudt.edu.cn/">National University of Defense Technology</a></div>
    <div class="tl-sub">Jointly trained with the Intelligent Game and Decision Lab (IGDL), working with Prof. <a href="https://qingyonghu.github.io/">Qingyong Hu</a></div>
  </li>
  <li>
    <span class="tl-period">2018.09 — 2022.06</span>
    <div class="tl-body"><a href="https://english.nudt.edu.cn/">National University of Defense Technology</a></div>
  </li>
</ul>

</div>

<!-- ============================================================
     OPTIONAL SECTIONS — uncomment and fill in when you have the
     content. Each block is self-contained and already styled.
     ============================================================

<div class="section-card" markdown="1">

# 🏆 Honors and Awards

<ul class="timeline">
  <li>
    <span class="tl-period">2025</span>
    <div class="tl-body">National Scholarship</div>
  </li>
</ul>

</div>

<div class="section-card" markdown="1">

# 💬 Invited Talks

<ul class="timeline">
  <li>
    <span class="tl-period">2026.05</span>
    <div class="tl-body"><strong>Talk title here</strong></div>
    <div class="tl-sub"><a href="#">▶ Watch Video</a></div>
  </li>
</ul>

</div>

<div class="section-card" markdown="1">

# 🧑‍🏫 Academic Services

<p style="margin-bottom: 0.7rem;">Reviewer for:</p>
<div class="research-tags">
  <span class="research-tag">NeurIPS</span>
  <span class="research-tag">ICML</span>
  <span class="research-tag">ICLR</span>
  <span class="research-tag">CVPR</span>
  <span class="research-tag">ACL</span>
</div>

</div>

============================================================ -->
