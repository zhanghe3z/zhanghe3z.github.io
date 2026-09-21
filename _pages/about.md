---
layout: about
title: about
permalink: /
subtitle:
description: Shangzhan Zhang - PhD student at Oxford VGG interested in agents, VLMs, and physical foundation models
keywords: Shangzhan Zhang, Oxford VGG, agents, VLMs, physical foundation models, computer vision, generative models, deep learning

profile:
  align: right
  image:
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a first-year PhD student at <a href="https://www.robots.ox.ac.uk/~vgg/" target="_blank">Oxford VGG</a>, advised by Prof. <a href="https://chrirupp.github.io/" target="_blank">Christian Rupprecht</a>, funded by <a href="https://www.ox.ac.uk/admissions/graduate/fees-and-funding/fees-funding-and-scholarship-search/scholarships-a-z-listing" target="_blank">Oxford-DeepMind Graduate Scholarship</a>.

My research interests lie in **agents**, **VLMs**, and **physical foundation models**. I’d love to exchange ideas with others who share similar interests

<style>
.selected-work { margin: 2.5rem 0; }
.selected-work-list { list-style: none; padding: 0; margin: 0; }
.work-item {
  display: grid;
  grid-template-columns: 52px minmax(0, 1fr);
  gap: 20px;
  padding: 22px 0;
  border-bottom: 1px solid var(--global-divider-color);
}
.work-item:last-child { border-bottom: none; padding-bottom: 0; }
.work-year {
  padding-top: 3px;
  font-size: 0.85rem;
  color: var(--global-text-color-light);
  font-variant-numeric: tabular-nums;
}
.work-title { font-size: 1.05rem; font-weight: 500; line-height: 1.45; margin: 0 0 6px; }
.work-title a { color: var(--global-text-color); }
.work-title a:hover { color: var(--global-theme-color); }
.work-authors { font-size: 0.82rem; line-height: 1.5; color: var(--global-text-color-light); margin: 0 0 6px; }
.work-authors strong { color: var(--global-text-color); font-weight: 500; }
.work-venue { font-size: 0.82rem; margin: 0 0 8px; }
.work-highlight { color: var(--global-theme-color); font-weight: 500; }
.work-summary { font-size: 0.92rem; line-height: 1.6; margin: 0 0 10px; }
.work-links { display: flex; flex-wrap: wrap; gap: 8px 18px; font-size: 0.82rem; font-weight: 500; }
.selected-work a:focus-visible { outline: 2px solid var(--global-theme-color); outline-offset: 4px; }
@media (max-width: 576px) {
  .work-item { grid-template-columns: 1fr; gap: 6px; }
  .work-year { padding-top: 0; }
}
.exp-section { margin-top: 2.5rem; }
.exp-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
}
@media (max-width: 768px) {
  .exp-grid { grid-template-columns: 1fr; gap: 0; }
}
.exp-col-title {
  font-size: 12px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: var(--global-text-color-light);
  margin-bottom: 10px;
}
.timeline-item {
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 14px 0;
  border-bottom: 1px solid var(--global-divider-color);
}
.timeline-item:last-child { border-bottom: none; }
.timeline-logo {
  width: 40px;
  height: 40px;
  object-fit: contain;
  opacity: 0.5;
  transition: opacity 0.2s ease;
  flex: 0 0 40px;
}
.timeline-item:hover .timeline-logo { opacity: 1; }
.timeline-info { flex: 1 1 auto; min-width: 0; }
.timeline-info h3 {
  font-size: 1.02rem;
  font-weight: 500;
  margin: 0 0 2px 0 !important;
  line-height: 1.3;
  color: var(--global-text-color);
  transition: color 0.2s ease;
}
.timeline-item:hover .timeline-info h3 { color: var(--global-theme-color); }
.timeline-info h3 a { color: inherit; text-decoration: none; }
.timeline-info h3 a:hover { color: var(--global-theme-color); }
.timeline-role {
  font-size: 0.82rem;
  line-height: 1.35;
  color: var(--global-text-color-light);
  margin: 0 !important;
}
.timeline-period {
  flex: 0 0 auto;
  align-self: center;
  text-align: right;
  white-space: nowrap;
  font-size: 0.78rem;
  font-weight: 500;
  color: var(--global-text-color-light);
  font-variant-numeric: tabular-nums;
  letter-spacing: 0.01em;
  min-width: 88px;
}
.remote-tag {
  display: inline-block;
  font-size: 0.65rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  padding: 1px 6px;
  margin-left: 6px;
  border: 1px solid var(--global-divider-color);
  border-radius: 3px;
  color: var(--global-text-color-light);
  vertical-align: middle;
}
</style>

<section class="selected-work" aria-labelledby="selected-work-heading">
  <h2 id="selected-work-heading">Selected Work</h2>
  <ul class="selected-work-list">
    <li class="work-item">
      <span class="work-year">2026</span>
      <div>
        <h3 class="work-title"><a href="https://arxiv.org/abs/2604.14141">Geometric Context Transformer for Streaming 3D Reconstruction</a></h3>
        <p class="work-authors">Lin-Zhuo Chen*, Jian Gao*, <strong>Shangzhan Zhang*</strong>, Yihang Chen, Nan Xue, Jianyuan Wang, Christian Rupprecht, Xun Cao, Xing Zhu, Yujun Shen, Yao Yao, Yinghao Xu</p>
        <p class="work-venue">ECCV 2026 · <strong class="work-highlight">Best Paper Candidate · Oral</strong></p>
        <p class="work-summary">Reconstructing 3D scenes from streaming video with a geometric context transformer that maintains spatial consistency over long sequences.</p>
        <div class="work-links" aria-label="Geometric Context Transformer resources">
          <a href="https://technology.robbyant.com/lingbot-map">Project</a>
          <a href="https://arxiv.org/abs/2604.14141">Paper</a>
          <a href="https://github.com/robbyant/lingbot-map">Code</a>
        </div>
      </div>
    </li>
    <li class="work-item">
      <span class="work-year">2026</span>
      <div>
        <h3 class="work-title"><a href="https://vggt-omega.github.io/">VGGT-Ω</a></h3>
        <p class="work-authors">Jianyuan Wang, Minghao Chen, <strong>Shangzhan Zhang</strong>, Nikita Karaev, Johannes Schönberger, Patrick Labatut, Piotr Bojanowski, David Novotny, Andrea Vedaldi, Christian Rupprecht</p>
        <p class="work-venue">CVPR 2026 · <span class="work-highlight">Best Paper Finalist · Oral</span></p>
        <p class="work-summary">Scaling feed-forward 3D reconstruction to learn spatial representations that also support language alignment and vision-language-action models.</p>
        <div class="work-links" aria-label="VGGT-Ω resources">
          <a href="https://vggt-omega.github.io/">Project</a>
          <a href="https://arxiv.org/abs/2605.15195">Paper</a>
          <a href="https://github.com/facebookresearch/vggt-omega">Code</a>
        </div>
      </div>
    </li>
    <li class="work-item">
      <span class="work-year">2026</span>
      <div>
        <h3 class="work-title"><a href="https://openaccess.thecvf.com/content/CVPR2026/html/Tang_GUI-SAGE_Enhancing_GUI_Automation_with_Self-Explanatory_Learning_CVPR_2026_paper.html">GUI-SAGE: Enhancing GUI Automation with Self-Explanatory Learning</a></h3>
        <p class="work-authors">Fei Tang, Zhangxuan Gu, Zhengxi Lu, <strong>Shangzhan Zhang</strong>, Zhengwen Zeng, Shuheng Shen, Changhua Meng, Yuchen Yan, Wenqi Zhang, Yongliang Shen, Weiming Lu, Yueting Zhuang</p>
        <p class="work-venue">CVPR 2026</p>
        <p class="work-summary">Improving GUI agents through self-explanatory reasoning and reinforcement learning, with entropy-aware credit assignment for more effective action learning.</p>
        <div class="work-links" aria-label="GUI-SAGE resources">
          <a href="https://openaccess.thecvf.com/content/CVPR2026/papers/Tang_GUI-SAGE_Enhancing_GUI_Automation_with_Self-Explanatory_Learning_CVPR_2026_paper.pdf">Paper</a>
        </div>
      </div>
    </li>
    <li class="work-item">
      <span class="work-year">2025</span>
      <div>
        <h3 class="work-title"><a href="https://zhanghe3z.github.io/FLARE/">FLARE: Feed-forward Geometry, Appearance and Camera Estimation from Uncalibrated Sparse Views</a></h3>
        <p class="work-authors"><strong>Shangzhan Zhang*</strong>, Jianyuan Wang*, Yinghao Xu*, Nan Xue, Christian Rupprecht, Xiaowei Zhou, Yujun Shen, Gordon Wetzstein</p>
        <p class="work-venue">CVPR 2025</p>
        <p class="work-summary">Jointly estimating cameras, 3D geometry, and appearance from a few unposed images in a single forward pass.</p>
        <div class="work-links" aria-label="FLARE resources">
          <a href="https://zhanghe3z.github.io/FLARE/">Project</a>
          <a href="https://arxiv.org/abs/2502.12138">Paper</a>
          <a href="https://github.com/robbyant-research/FLARE">Code</a>
        </div>
      </div>
    </li>
    <li class="work-item">
      <span class="work-year">2024</span>
      <div>
        <h3 class="work-title"><a href="https://arxiv.org/abs/2404.17569">MaPa: Text-driven Photorealistic Material Painting for 3D Shapes</a></h3>
        <p class="work-authors"><strong>Shangzhan Zhang</strong>, Sida Peng, Tao Xu, Yuanbo Yang, Tianrun Chen, Nan Xue, Yujun Shen, Hujun Bao, Ruizhen Hu, Xiaowei Zhou</p>
        <p class="work-venue">SIGGRAPH 2024</p>
        <p class="work-summary">An early exploration of LLM tool calling for graphics, enabling language-guided editing of procedural materials for 3D shapes.</p>
        <div class="work-links" aria-label="MaPa resources">
          <a href="https://arxiv.org/abs/2404.17569">Paper</a>
        </div>
      </div>
    </li>
  </ul>
</section>

## Experience

<div class="exp-section">
<div class="exp-grid">

<div class="exp-col">
  <div class="exp-col-title">Education</div>

  <div class="timeline-item">
    <img class="timeline-logo" src="{{ '/assets/img/logos/oxford.png' | relative_url }}" alt="Oxford" onerror="this.style.display='none'">
    <div class="timeline-info">
      <h3><a href="https://www.ox.ac.uk/" target="_blank">University of Oxford</a></h3>
      <p class="timeline-role">PhD, advised by Prof. Christian Rupprecht</p>
    </div>
    <span class="timeline-period">2025 &mdash;</span>
  </div>

  <div class="timeline-item">
    <img class="timeline-logo" src="{{ '/assets/img/logos/zju.png' | relative_url }}" alt="ZJU" onerror="this.style.display='none'">
    <div class="timeline-info">
      <h3><a href="https://www.zju.edu.cn/english/" target="_blank">Zhejiang University</a></h3>
      <p class="timeline-role">M.Eng. in Computer Science, advised by Prof. Sida Peng and Prof. Xiaowei Zhou</p>
    </div>
    <span class="timeline-period">2022 &mdash; 2025</span>
  </div>

  <div class="timeline-item">
    <img class="timeline-logo" src="{{ '/assets/img/logos/zju.png' | relative_url }}" alt="ZJU" onerror="this.style.display='none'">
    <div class="timeline-info">
      <h3><a href="https://www.zju.edu.cn/english/" target="_blank">Zhejiang University</a></h3>
      <p class="timeline-role">B.E. in Electronic Science and Technology</p>
    </div>
    <span class="timeline-period">2018 &mdash; 2022</span>
  </div>

</div>

<div class="exp-col">
  <div class="exp-col-title">Experience</div>

  <div class="timeline-item">
    <img class="timeline-logo" src="{{ '/assets/img/logos/adobe.png' | relative_url }}" alt="Adobe Research" onerror="this.style.display='none'">
    <div class="timeline-info">
      <h3><a href="https://research.adobe.com/" target="_blank">Adobe Research</a></h3>
      <p class="timeline-role">Research Intern, mentored by Dr. Zifan Shi and Dr. Kalyan Sunkavalli</p>
    </div>
    <span class="timeline-period">2025</span>
  </div>

  <div class="timeline-item">
    <img class="timeline-logo" src="{{ '/assets/img/logos/ant.png' | relative_url }}" alt="Ant Research" onerror="this.style.display='none'">
    <div class="timeline-info">
      <h3><a href="https://www.antgroup.com/en" target="_blank">Ant Research</a></h3>
      <p class="timeline-role">Research Intern, mentored by Dr. Yinghao Xu</p>
    </div>
    <span class="timeline-period">2025</span>
  </div>

  <div class="timeline-item">
    <img class="timeline-logo" src="{{ '/assets/img/logos/stanford.png' | relative_url }}" alt="Stanford" onerror="this.style.display='none'">
    <div class="timeline-info">
      <h3><a href="https://www.stanford.edu/" target="_blank">Stanford University</a> <span class="remote-tag">Remote</span></h3>
      <p class="timeline-role">Guided by Dr. Yinghao Xu and Prof. Gordon Wetzstein</p>
    </div>
    <span class="timeline-period">2024</span>
  </div>

  <div class="timeline-item">
    <img class="timeline-logo" src="{{ '/assets/img/logos/ant.png' | relative_url }}" alt="Ant Research" onerror="this.style.display='none'">
    <div class="timeline-info">
      <h3><a href="https://www.antgroup.com/en" target="_blank">Ant Research</a></h3>
      <p class="timeline-role">Research Intern, mentored by Dr. Nan Xue and Dr. Yujun Shen</p>
    </div>
    <span class="timeline-period">2023 &mdash; 2025</span>
  </div>

</div>

</div>
</div>
