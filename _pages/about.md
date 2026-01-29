---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Smooth scrolling */
  html {
    scroll-behavior: smooth;
  }
  
  /* Section spacing */
  .page-section {
    padding-top: 80px;
    margin-top: -80px;
  }
  
  /* Publications tabs */
  .pub-tabs {
    margin-bottom: 20px;
  }
  
  .pub-tab-button {
    padding: 8px 20px;
    margin-right: 10px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
    background-color: #f0f0f0;
    color: #333;
    transition: all 0.3s;
  }
  
  .pub-tab-button.active {
    background-color: #4285f4;
    color: white;
  }
  
  .pub-tab-button:hover {
    background-color: #e0e0e0;
  }
  
  .pub-tab-button.active:hover {
    background-color: #3367d6;
  }
  
  .pub-note {
    color: #666;
    font-size: 14px;
    font-style: italic;
    margin-bottom: 20px;
  }
  
  .publication-item {
    display: flex;
    align-items: center;
    margin-bottom: 40px;
    padding-bottom: 30px;
    border-bottom: 1px solid #e0e0e0;
  }
  
  .publication-item:last-child {
    border-bottom: none;
  }
  
  .pub-image {
    flex: 0 0 300px;
    margin-right: 35px;
  }
  
  .pub-image img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }
  
  .pub-content {
    flex: 1;
  }
  
  .pub-title {
    font-size: 17px;
    font-weight: 600;
    margin-bottom: 8px;
    line-height: 1.4;
  }
  
  .pub-authors {
    font-size: 15px;
    margin-bottom: 6px;
    line-height: 1.6;
  }
  
  .pub-authors a {
    color: #4285f4;
    text-decoration: none;
  }
  
  .pub-authors a:hover {
    text-decoration: underline;
  }
  
  .pub-venue {
    color: #d32f2f;
    font-style: italic;
    font-size: 15px;
    margin-bottom: 8px;
  }
  
  .pub-links a {
    display: inline-block;
    margin-right: 15px;
    color: #4285f4;
    text-decoration: none;
    font-size: 15px;
  }
  
  .pub-links a:hover {
    text-decoration: underline;
  }
  
  .tab-content {
    display: none;
  }
  
  .tab-content.active {
    display: block;
  }

  /* Education section */
  .education-item {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
  }
  
  .edu-logo {
    flex: 0 0 60px;
    margin-right: 20px;
  }
  
  .edu-logo img {
    width: 60px;
    height: 60px;
    object-fit: contain;
  }
  
  .edu-content {
    flex: 1;
  }
  
  .edu-degree {
    font-size: 16px;
    line-height: 1.6;
  }
</style>

I am a Master's student in Data Science at the University of Pennsylvania. Previously, I earned a Bachelor's degree in Mathematics from UW–Madison. I am currently a visiting Research Assistant at UIUC, where I am fortunate to work with Prof. [Ismini Lourentzou](https://isminoula.github.io/) and Prof. [James M. Rehg](https://rehg.org/). At Penn, I was fortunate to work with Prof. [Chris Callison-Burch](https://www.cis.upenn.edu/~ccb/) and Prof. [Dan Roth](https://www.cis.upenn.edu/~danroth/).

My research focuses on the capability of embodied agents and applying them for perception, reasoning, and planning in the physical world. My work lies at the intersection of **Multimodal Learning** (VLMs/MLLMs), **Robot Learning** (Robotic Foundation Models, VLA), and **Deep Reinforcement Learning**.

## News
---

<div id="publications" class="page-section"></div>

<h2>Publications</h2>

<div class="pub-tabs">
  <button id="tab-selected" class="pub-tab-button active">Selected</button>
  <button id="tab-full" class="pub-tab-button">Full</button>
</div>

<div id="selected-tab" class="tab-content active">
  <div class="publication-item">
    <div class="pub-image">
      <img src="/images/spatialreasoner.png" alt="SpatialReasoner-R1">
    </div>
    <div class="pub-content">
      <div class="pub-title">Fine-Grained Preference Optimization Improves Spatial Reasoning in VLMs</div>
      <div class="pub-authors">
        Yifan Shen*, <strong>Yuanzhe Liu*</strong> (*equal contribution), Jingyuan Zhu, Xu Cao, Xiaofeng Zhang, Yixiao He, Wenming Ye, James M. Rehg, Ismini Lourentzou
      </div>
      <div class="pub-venue">NeurIPS, 2025</div>
      <div class="pub-links">
        <a href="https://plan-lab.github.io/projects/spatialreasoner/">Webpage</a>
        <a href="https://arxiv.org/pdf/2506.21656">Paper</a>
      </div>
    </div>
  </div>
  <div class="publication-item">
    <div class="pub-image">
      <img src="/images/palm.png" alt="PALM">
    </div>
    <div class="pub-content">
      <div class="pub-title">PALM: Progress-Aware Policy Learning via Affordance Reasoning for Long-Horizon Robotic Manipulation</div>
      <div class="pub-authors">
        <strong>Yuanzhe Liu</strong>, Jingyuan Zhu, Yuchen Mo, Gen Li, Xu Cao, Jin Jin, Yifan Shen, Zhengyuan Li, Tianjiao Yu, Wenzhen Yuan, Fangqiang Ding, Ismini Lourentzou
      </div>
      <div class="pub-venue">Preprint, 2026</div>
      <div class="pub-links">
        <a href="https://arxiv.org/pdf/2601.07060">Paper</a>
      </div>
    </div>
  </div>
</div>

<div id="full-tab" class="tab-content">
  <div class="publication-item">
    <div class="pub-image">
      <img src="/images/spatialreasoner.png" alt="SpatialReasoner-R1">
    </div>
    <div class="pub-content">
      <div class="pub-title">Fine-Grained Preference Optimization Improves Spatial Reasoning in VLMs</div>
      <div class="pub-authors">
        Yifan Shen*, <strong>Yuanzhe Liu*</strong> (*equal contribution), Jingyuan Zhu, Xu Cao, Xiaofeng Zhang, Yixiao He, Wenming Ye, James M. Rehg, Ismini Lourentzou
      </div>
      <div class="pub-venue">NeurIPS, 2025</div>
      <div class="pub-links">
        <a href="https://plan-lab.github.io/projects/spatialreasoner/">Webpage</a>
        <a href="https://arxiv.org/pdf/2506.21656">Paper</a>
      </div>
    </div>
  </div>
  <div class="publication-item">
    <div class="pub-image">
      <img src="/images/palm.png" alt="PALM">
    </div>
    <div class="pub-content">
      <div class="pub-title">PALM: Progress-Aware Policy Learning via Affordance Reasoning for Long-Horizon Robotic Manipulation</div>
      <div class="pub-authors">
        <strong>Yuanzhe Liu</strong>, Jingyuan Zhu, Yuchen Mo, Gen Li, Xu Cao, Jin Jin, Yifan Shen, Zhengyuan Li, Tianjiao Yu, Wenzhen Yuan, Fangqiang Ding, Ismini Lourentzou
      </div>
      <div class="pub-venue">Preprint, 2026</div>
      <div class="pub-links">
        <a href="https://arxiv.org/pdf/2601.07060">Paper</a>
      </div>
    </div>
  </div>
  <div class="publication-item">
    <div class="pub-image">
      <img src="/images/deeptrace.png" alt="DeeptraceReward">
    </div>
    <div class="pub-content">
      <div class="pub-title">DeeptraceReward: Learning Human-Perceived Fakeness in Generated Videos with Multimodal LLMs</div>
      <div class="pub-authors">
        Xingyu Fu*, Siyi Liu*, Yinuo Xu*, Pan Lu, Guangqiuse Hu, Tianbo Yang, Taran Anantasagar, Christopher Shen, Yikai Mao, <strong>Yuanzhe Liu</strong>, Keyush Shah, Chung Un Lee, Yejin Choi, James Zou, Dan Roth, Chris Callison-Burch
      </div>
      <div class="pub-venue">Preprint, 2025</div>
      <div class="pub-links">
        <a href="https://deeptracereward.github.io/">Webpage</a>
        <a href="https://arxiv.org/pdf/2509.22646">Paper</a>
        <a href="https://github.com/deeptracereward/deeptracereward">Code</a>
        <a href="https://huggingface.co/datasets/DeeptraceReward/RewardData">Dataset</a>
      </div>
    </div>
  </div>
  <div class="publication-item">
    <div class="pub-image">
      <img src="/images/Core3d.png" alt="CoRe3D">
    </div>
    <div class="pub-content">
      <div class="pub-title">CoRe3D: Collaborative Reasoning as a Foundation for 3D Intelligence</div>
      <div class="pub-authors">
        Tianjiao Yu, Xinzhuo Li, Yifan Shen, <strong>Yuanzhe Liu</strong>, Ismini Lourentzou
      </div>
      <div class="pub-venue">Preprint, 2025</div>
      <div class="pub-links">
        <a href="https://arxiv.org/pdf/2512.12768">Paper</a>
      </div>
    </div>
  </div>
</div>

<script>
(function() {
  function switchTab(tabName) {
    console.log('Switching to tab:', tabName);
    document.querySelectorAll('.tab-content').forEach(function(tab) {
      tab.classList.remove('active');
    });
    document.querySelectorAll('.pub-tab-button').forEach(function(btn) {
      btn.classList.remove('active');
    });
    var targetTab = document.getElementById(tabName + '-tab');
    console.log('Target tab element:', targetTab);
    if (targetTab) {
      targetTab.classList.add('active');
    }
    var selectedBtn = document.getElementById('tab-selected');
    var fullBtn = document.getElementById('tab-full');
    if (tabName === 'selected' && selectedBtn) {
      selectedBtn.classList.add('active');
    } else if (tabName === 'full' && fullBtn) {
      fullBtn.classList.add('active');
    }
  }
  var selectedBtn = document.getElementById('tab-selected');
  var fullBtn = document.getElementById('tab-full');
  if (selectedBtn) {
    selectedBtn.addEventListener('click', function() {
      switchTab('selected');
    });
  }
  if (fullBtn) {
    fullBtn.addEventListener('click', function() {
      switchTab('full');
    });
  }
  switchTab('selected');
})();
</script>

---

<div id="educations" class="page-section"></div>
<h2>Educations</h2>
<div class="education-item">
  <div class="edu-logo">
    <img src="/images/upenn_logo.png" alt="University of Pennsylvania">
  </div>
  <div class="edu-content">
    <div class="edu-degree"><strong>M.S. in Data Science</strong>, University of Pennsylvania, 2024-2026</div>
  </div>
</div>
<div class="education-item">
  <div class="edu-logo">
    <img src="/images/wisc_logo2.png" alt="University of Wisconsin-Madison">
  </div>
  <div class="edu-content">
    <div class="edu-degree"><strong>B.S. in Mathematics</strong>, University of Wisconsin–Madison, 2019-2023</div>
  </div>
</div>

---

<div id="experiences" class="page-section"></div>

## Experiences

- **[2025/07]** : Research Intern at UIUC, Champaign IL
- **[2025/05]** : LLM Algorithm Intern @ Baidu, Beijing
- **[2024/08]** : Research Intern at UPenn, Philadelphia PA
- **[2024/05]** : LLM Algorithm Intern @ Alibaba Cloud, Hangzhou

---

<div id="others" class="page-section"></div>

## Services

- **Conference Reviewer:** CVPR, AAAI, NeurIPS
- **Workshops Reviewer:** CVPR 2026 Workshop on Computer Vision for Children (CV4CHL)

### Hobbies
Outside of research, I'm passionate about basketball, billiards, and strength training. I'm an avid powerlifter with a combined total of 358kg across the three main lifts (squat, bench press, and deadlift). While I'm not a professional, I deeply enjoy the process of pushing my physical limits and the mental discipline it requires. I look forward to continuing this journey and setting new personal records during my PhD years ahead.

