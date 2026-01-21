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
    margin-bottom: 40px;
    padding-bottom: 30px;
    border-bottom: 1px solid #e0e0e0;
  }
  
  .publication-item:last-child {
    border-bottom: none;
  }
  
  .pub-image {
    flex: 0 0 250px;
    margin-right: 30px;
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
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 10px;
    line-height: 1.4;
  }
  
  .pub-authors {
    margin-bottom: 8px;
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
    margin-bottom: 8px;
  }
  
  .pub-links a {
    display: inline-block;
    margin-right: 15px;
    color: #4285f4;
    text-decoration: none;
    font-size: 14px;
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
</style>

I am a Master's student in Data Science at the University of Pennsylvania. Previously, I earned a Bachelor's degree in Mathematics from UW–Madison. I am currently a visiting Research Assistant at UIUC, where I am fortunate to work with Prof. [Ismini Lourentzou](https://isminoula.github.io/) and Prof. [James M. Rehg](https://rehg.org/). At Penn, I was fortunate to work with Prof. [Chris Callison-Burch](https://www.cis.upenn.edu/~ccb/) and Prof. [Dan Roth](https://www.cis.upenn.edu/~danroth/).

My research focuses on the capability of embodied agents and applying them for perception, reasoning, and planning in the physical world. My work lies at the intersection of **Multimodal Learning** (VLMs/MLLMs), **Robot Learning** (Robotic Foundation Models, VLA), and **Deep Reinforcement Learning**.

## News


---

<div id="publications" class="page-section"></div>

## Publications

<div class="pub-tabs">
  <button class="pub-tab-button active" onclick="switchTab('selected')">Selected</button>
  <button class="pub-tab-button" onclick="switchTab('full')">Full</button>
</div>

<div id="selected-tab" class="tab-content active">
  <p class="pub-note">(The Selected tab highlights publications that best represent my expertise)</p>
  
  <!-- Selected Publications -->
  <div class="publication-item">
    <div class="pub-image">
      <img src="/images/spatialreasoner.png" alt="SpatialReasoner-R1">
    </div>
    <div class="pub-content">
      <div class="pub-title">Fine-Grained Preference Optimization Improves Spatial Reasoning in VLMs</div>
      <div class="pub-authors">
        Yifan Shen, <strong>Yuanzhe Liu</strong>, Jingyuan Zhu, Xu Cao, Xiaofeng Zhang, Yixiao He, Wenming Ye, James M. Rehg, Ismini Lourentzou
      </div>
      <div class="pub-venue">NeurIPS, 2025</div>
      <div class="pub-links">
        <a href="https://plan-lab.github.io/projects/spatialreasoner/">Webpage</a>
        <a href="https://arxiv.org/pdf/2506.21656">Paper</a>
        <a href="#" style="color: #999; pointer-events: none;">Code (Coming Soon)</a>
      </div>
    </div>
  </div>
  
</div>

<div id="full-tab" class="tab-content">
  <p>Full list of publications will be displayed here.</p>
</div>

---

<div id="educations" class="page-section"></div>

## Educations

- **M.S. in Data Science**, University of Pennsylvania, 2024-2026
- **B.S. in Mathematics**, University of Wisconsin–Madison, 2020-2024

---

<div id="experiences" class="page-section"></div>

## Experiences

- **Research Assistant** at Microsoft Research, 2025.
- **Research Intern** at Tencent AI Lab and Robotics X Lab, 2020-2022 (Multiple internship terms).
- **Machine Learning Intern** at Meituan, 2019.

---

<div id="others" class="page-section"></div>

## Others

### Services

**Conference Reviewer:** ICML, ICLR, NeurIPS (Top Reviewer in NeurIPS 2023), ACL/ARR, ICRA, AAMAS.

**Journal Reviewer:** IEEE Robotics and Automation Letters (RA-L), IEEE Transactions on Neural Networks and Learning Systems (TNNLS), IEEE Transactions on Artificial Intelligence (TAI), Machine Learning, Journal of Artificial Intelligence Research.

**Teaching Assistant:** COMP 4211 Machine Learning, HKUST; COMP 1021 Introduction to Computer Science, HKUST

### Hobbies

In my leisure time, I enjoy sports like running, table tennis, and swimming.

<script>
function switchTab(tabName) {
  // Hide all tabs
  document.querySelectorAll('.tab-content').forEach(tab => {
    tab.classList.remove('active');
  });
  
  // Remove active class from all buttons
  document.querySelectorAll('.pub-tab-button').forEach(btn => {
    btn.classList.remove('active');
  });
  
  // Show selected tab
  document.getElementById(tabName + '-tab').classList.add('active');
  
  // Add active class to clicked button
  event.target.classList.add('active');
}
</script>
