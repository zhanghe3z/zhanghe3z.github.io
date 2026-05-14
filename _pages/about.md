---
layout: about
title: about
permalink: /
subtitle:
description: Shangzhan Zhang - PhD student at Oxford VGG researching generative models, 3D vision, and model-based reinforcement learning
keywords: Shangzhan Zhang, Oxford VGG, computer vision, generative models, 3D vision, reinforcement learning, deep learning, AI research

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

I am a first-year PhD student at <a href="https://www.robots.ox.ac.uk/~vgg/" target="_blank">Oxford VGG</a>, advised by Prof. <a href="https://chrirupp.github.io/" target="_blank">Christian Rupprecht</a>, funded by <a href="https://www.ox.ac.uk/admissions/graduate/fees-and-funding/fees-funding-and-scholarship-search/scholarships-a-z-listing" target="_blank">Oxford-DeepMind Graduate Scholarship</a>. My research interests lie in generative models, multimodal models, and 3D foundation models. I’d really appreciate the chance to exchange ideas with anyone who shares similar interests!

<style>
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
      <p class="timeline-role">Research Intern, mentored by Zifan Shi and Kalyan Sunkavalli</p>
    </div>
    <span class="timeline-period">May &mdash; Oct 2025</span>
  </div>

  <div class="timeline-item">
    <img class="timeline-logo" src="{{ '/assets/img/logos/stanford.png' | relative_url }}" alt="Stanford" onerror="this.style.display='none'">
    <div class="timeline-info">
      <h3><a href="https://www.stanford.edu/" target="_blank">Stanford University</a> <span class="remote-tag">Remote</span></h3>
      <p class="timeline-role">Guided by Dr. Yinghao Xu and Prof. Gordon Wetzstein</p>
    </div>
    <span class="timeline-period">Summer 2024</span>
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
