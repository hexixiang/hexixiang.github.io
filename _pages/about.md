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
.interest-list {
  display: flex;
  flex-direction: column;
  gap: 0.55rem;
}
.interest-row {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.35rem 0.6rem;
}
.interest-works {
  font-size: 0.9em;
  color: #555;
}
.interest-works a {
  color: #1a4f9c;
  font-weight: 600;
}
.first-author {
  display: inline-block;
  margin-left: 6px;
  padding: 1px 8px;
  border-radius: 4px;
  background: #fff1e6;
  color: #c2410c;
  font-size: 0.78em;
  font-weight: 700;
  white-space: nowrap;
  vertical-align: 1px;
}
.resource-list { margin: 0; padding-left: 1.2em; }
.resource-list li { margin: 0 0 12px 0; line-height: 1.55; }
.resource-list li:last-child { margin-bottom: 0; }
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
So far I have first-authored papers at <strong>NeurIPS</strong>, <strong>ICML</strong> and <strong>ICME</strong>, and co-authored work at <strong>CVPR</strong> (Highlight), <strong>AAAI</strong> (Oral) and <strong>IJCAI</strong>.
<br><br>
I am always glad to talk about research or collaboration &mdash; feel free to reach out by <a href="mailto:hexixiang@nudt.edu.cn">email</a>.
</div>

<div style="margin-top: 12px;">
  <a href="https://github.com/hexixiang"><img src="https://img.shields.io/github/stars/hexixiang?affiliations=OWNER%2CCOLLABORATOR&style=flat&logo=github&logoColor=000000&label=GitHub%20Stars&labelColor=f0f0f0&color=8fb9ef" alt="GitHub Stars"></a>
</div>

<div style="margin-top: 18px; background: #f4f7ff; border: 1px solid #d8e3fb; border-radius: 12px; padding: 14px 18px;">
  <div style="font-size: 0.82em; font-weight: 700; color: #1a73e8; text-transform: uppercase; letter-spacing: 0.6px; margin-bottom: 10px;">Research Interests</div>
  <div class="interest-list">
    <div class="interest-row"><span class="research-tag">📊 Data-Centric Post-Training</span><span class="interest-works"><a href="https://arxiv.org/abs/2507.03673">TACOS</a></span></div>
    <div class="interest-row"><span class="research-tag">🎯 RL for LLM Reasoning</span><span class="interest-works"><a href="https://arxiv.org/abs/2605.21125">AVSPO</a></span></div>
    <div class="interest-row"><span class="research-tag">🧪 Knowledge Distillation</span><span class="interest-works"><a href="https://arxiv.org/abs/2609.02548">MT-SDPO</a></span></div>
    <div class="interest-row"><span class="research-tag">🔍 Trustworthy LLMs</span><span class="interest-works"><a href="https://arxiv.org/abs/2603.22812">Efficient Hallucination Detection</a>, <a href="https://arxiv.org/abs/2606.17953">CALRD</a></span></div>
    <div class="interest-row"><span class="research-tag">👁️ Multimodal Reasoning</span><span class="interest-works"><a href="https://arxiv.org/abs/2606.00148">StemBind</a>, <a href="https://arxiv.org/abs/2603.22763">ENC-Bench</a></span></div>
  </div>
</div>

</div>

<div class="section-card" markdown="1">

# 🔥 News

<ul style="margin:0; padding-left:1.2em;">
  <li><p style='text-align:justify; margin:4px 0'><i>2026.09</i>: &nbsp;🎉🎉 <strong>StemBind</strong> is accepted by <span style="color:#c0392b; font-weight:600;">NeurIPS 2026</span>.</p></li>
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

<h2 id="preprints">Preprints</h2>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/pub/mtsdpo.jpg' alt="MT-SDPO: answer-verified multi-teacher self-distillation pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Learn from Whoever Is Right: Answer-Verified Multi-Teacher Distillation for Multi-Domain LLMs**](https://arxiv.org/abs/2609.02548)

🧑‍💻 **Xixiang He**, Xingming Li, Baiqi Wu, Qiyao Sun, Xuanyu Ji, Ao Cheng, Qingyong Hu# <span class="first-author">First Author</span>

arXiv preprint, 2026.

[[Paper]](https://arxiv.org/abs/2609.02548) \| [[Github]](https://github.com/hexixiang/MT-SDPO)

</div>
</div>

<h2 id="accepted-papers">Accepted Papers</h2>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/pub/stembind.jpg' alt="StemBind overview: nine operations, shared-stem P/R/F probes, and S1-S4 process annotation" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**StemBind: When MLLMs Get Lost Between Rules and Instances in Abstract Visual Reasoning**](https://arxiv.org/abs/2606.00148)

🧑‍💻 **Xixiang He**, Baiqi Wu, Xingming Li, Ao Cheng, Qiyao Sun, Xuanyu Ji, Qingyong Hu# <span class="first-author">First Author</span>

🏛️ Conference on Neural Information Processing Systems **(NeurIPS)**, Evaluations & Datasets Track, 2026. <font color="red">CCF A</font>.

[[Paper]](https://arxiv.org/abs/2606.00148) \| [[Project]](https://hexixiang.github.io/StemBind/) \| [[Github]](https://github.com/hexixiang/StemBind) \| [[Dataset]](https://huggingface.co/datasets/user48271/Stembind)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/pub/avspo.jpg' alt="AVSPO framework: ACR monitor triggers virtual reward injection to restore advantage variance" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Advantage Collapse in Group Relative Policy Optimization: Diagnosis and Mitigation**](https://arxiv.org/abs/2605.21125)

🧑‍💻 **Xixiang He**, Qiyao Sun, Ao Cheng, Xingming Li, Xuanyu Ji, Hailun Lu, Runke Huang, Qingyong Hu# <span class="first-author">First Author</span>

🏛️ International Conference on Machine Learning **(ICML)**, 2026. <font color="red">CCF A</font>.

[[Paper]](https://arxiv.org/abs/2605.21125) \| [[Project]](https://qingyonghu.github.io/AVSPO/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2026</div><img src='images/pub/calrd.jpg' alt="CALRD teaser: MLLMs reach the right answer in middle layers and lose it to textual bias in late layers" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**MLLMs Get It Right, Then Get It Wrong: Tracing and Correcting Late-Layer Textual Bias**](https://arxiv.org/abs/2606.17953)

🧑‍💻 Xingming Li, Ao Cheng, Qiyao Sun, **Xixiang He**, Xuanyu Ji, Runke Huang, Qingyong Hu#

🏛️ International Joint Conference on Artificial Intelligence **(IJCAI-ECAI)**, 2026. <font color="red">CCF A</font>.

[[Paper]](https://arxiv.org/abs/2606.17953) \| [[Project]](https://qingyonghu.github.io/CALRD/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Highlight</div><img src='images/pub/encbench.jpg' alt="ENC-Bench overview of electronic navigational chart understanding tasks" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ENC-Bench: A Benchmark for Evaluating Multimodal Large Language Models in Electronic Navigational Chart Understanding**](https://arxiv.org/abs/2603.22763)

🧑‍💻 Ao Cheng, Xingming Li, Xuanyu Ji, **Xixiang He**, Qiyao Sun, Chunping Qiu, Runke Huang, Qingyong Hu#

🏛️ IEEE/CVF Conference on Computer Vision and Pattern Recognition **(CVPR)**, 2026. <font color="red">CCF A, Highlight</font>.

[[Paper]](https://arxiv.org/abs/2603.22763) \| [[Project]](https://qingyonghu.github.io/ENC-Bench/) \| [[Github]](https://github.com/QingyongHu/ENC-Bench)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/pub/hallucination.jpg' alt="Adaptive Bayesian estimation of semantic entropy for hallucination detection" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Efficient Hallucination Detection: Adaptive Bayesian Estimation of Semantic Entropy with Guided Semantic Exploration**](https://arxiv.org/abs/2603.22812)

🧑‍💻 Qiyao Sun, Xingming Li, **Xixiang He**, Ao Cheng, Xuanyu Ji, Hailun Lu, Runke Huang, Qingyong Hu#

🏛️ AAAI Conference on Artificial Intelligence **(AAAI)**, 2026. <font color="red">CCF A, Oral</font>.

[[Paper]](https://arxiv.org/abs/2603.22812) \| [[Project]](https://qingyonghu.github.io/Efficient-Hallucination-Detection/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='images/pub/tacos.jpg' alt="TACOS: open tagging and comparative scoring for instruction data selection" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**TACOS: Open Tagging and Comparative Scoring for Instruction Fine-Tuning Data Selection**](https://arxiv.org/abs/2507.03673)

🧑‍💻 **Xixiang He**, Hao Yu, Qiyao Sun, Ao Cheng, Tailai Zhang, Cong Liu, Shuxuan Guo# <span class="first-author">First Author</span>

🏛️ IEEE International Conference on Multimedia and Expo **(ICME)**, 2025. <font color="red">CCF B</font>.

[[Paper]](https://arxiv.org/abs/2507.03673) \| [[Github]](https://github.com/hexixiang/TACOS)

</div>
</div>

<div style="font-size: 0.92em; color: #666; margin-top: 14px;">
<i>#</i> Corresponding author. Full list on <a href="https://scholar.google.com/citations?user=724HNF4AAAAJ&hl=en">Google Scholar</a>.
</div>

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

# 🧰 Open-Source Resources

<ul class="resource-list">
  <li><strong>StemBind Benchmark</strong> &mdash; a shared-stem diagnostic benchmark for abstract visual reasoning in MLLMs: 2,298 stems and 19,533 perception / rule / full-item tasks, with S1&ndash;S4 process annotations and a public leaderboard.<br>
  <a href="https://huggingface.co/datasets/user48271/Stembind">[Dataset]</a> | <a href="https://github.com/hexixiang/StemBind">[Github]</a> | <a href="https://hexixiang.github.io/StemBind/#leaderboard">[Leaderboard]</a></li>
  <li><strong>MT-SDPO</strong> &mdash; training code for answer-verified multi-teacher distillation, with the SciKnowEval-L3 splits, teacher-generated SFT data and the frozen evaluation protocol.<br>
  <a href="https://github.com/hexixiang/MT-SDPO">[Github]</a></li>
  <li><strong>TACOS</strong> &mdash; instruction-tuning data selection code, the curated fine-tuning dataset, and the fine-tuning, inference and evaluation scripts.<br>
  <a href="https://github.com/hexixiang/TACOS">[Github]</a></li>
</ul>

</div>

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
