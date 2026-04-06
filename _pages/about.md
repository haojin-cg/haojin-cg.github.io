---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>
<!-- # Welcome to my homepage! -->

Hi, I am a Ph.D candidate in Information Science at the **Japan Advanced Institute of Science and Technology ([JAIST](https://www.jaist.ac.jp/english/))**, advised by [Prof. Haoran Xie](https://www.jaist.ac.jp/~xie/) (in [Human-Centered AI Lab](https://www.jaist.ac.jp/~xie/lab.html)). I received my M.S. degree in Computer Science (advised by [Prof. Shaojun Hu](https://cie.nwsuaf.edu.cn/szdw/fjs/2010110086/index.htm)) and my B.S. degree in Mechanical Engineering from [Northwest A&F University](https://en.nwsuaf.edu.cn/). My current research interest lies at **Controllable Video Generation and Robotics**. If you are interested in academic collaboration, please feel free to contact me by email.



<span class="anchor" id="news"></span>
# 📰 News

<div class="timeline-container">
<div class="timeline-item">
    <div class="timeline-date">2026.04</div>
    <div class="timeline-content">Our paper accepted by Computer & Graphic Journal.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2026.03</div>
    <div class="timeline-content">Our paper accepted by Frontiers of Architectural Research Journal.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2026.01</div>
    <div class="timeline-content">Our paper accepted by IEEE International Conference on Robotics and Automation(ICRA) 2026.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2025.09</div>
    <div class="timeline-content">Our paper accepted by The Association for Computer‑Aided Architectural Design Research in Asia (CAADRIA) 2025.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2024.06</div>
    <div class="timeline-content">Our recent work in RA-L is transfered to IEEE International Conference on Robotics and Automation (ICRA) 2024.</div>
  </div>


  <!-- <details class="timeline-details">
    <summary class="timeline-summary">
      <span class="summary-text">Show more history ▾</span>
    </summary>
  </details> -->
</div>

<style>
/* News Timeline Styling */
.timeline-container {
  position: relative;
  padding-left: 20px;
  border-left: 2px solid #e1e4e8;
  margin-bottom: 30px;
  margin-left: 8px;
}
.timeline-item { position: relative; margin-bottom: 16px; }
.timeline-item::before {
  content: ''; position: absolute; left: -27px; top: 5px;
  width: 12px; height: 12px; background-color: #0366d6;
  border-radius: 50%; border: 2px solid #fff;
}
.timeline-date { font-weight: 600; color: #0366d6; font-size: 0.95em; margin-bottom: 2px; }
.timeline-content { font-size: 0.95em; color: #24292e; }

/* 现代化的 Show more 按钮 */
.timeline-details summary {
  display: inline-flex; align-items: center;
  margin-left: -20px;
  padding: 6px 14px; background-color: #f6f8fa;
  border: 1px solid #e1e4e8; border-radius: 20px;
  font-size: 0.85em; font-weight: 600; color: #586069;
  cursor: pointer; transition: all 0.2s ease; list-style: none;
}
.timeline-details summary:hover { background-color: #e1e4e8; color: #24292e; }
.timeline-details summary::-webkit-details-marker { display: none; }
.timeline-details[open] summary .summary-text { content: "Show less ▴"; }

/* Global Paper Box Hover Effect */
.paper-box {
  display: flex;
  margin-bottom: 24px;
  border-radius: 8px;
  padding: 14px;
  border: 1px solid #ececec;
  background-color: #ffffff;
  transition: transform 0.25s cubic-bezier(0.2, 0.8, 0.2, 1), box-shadow 0.25s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.paper-box:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 24px rgba(0, 0, 0, 0.08);
  border-color: #e2e8f0;
}
.paper-box-image {
  flex: 0 0 32%;
  margin-right: 18px;
  border-radius: 8px;
  overflow: hidden;
  position: relative;
  transform: translateZ(0);
}
.paper-box-image video, .paper-box-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
.paper-box-text { flex: 1; }
.paper-box-text .title {
  font-weight: 600;
  font-size: 1.06em;
  color: #1f2d3d;
  text-decoration: none;
  transition: color 0.2s ease;
}
.paper-box-text .title:hover { color: #0366d6; }
.paper-box-text .authors { margin: 4px 0 3px 0; color: #333; font-size: 0.95em; }
.paper-box-text .venue { margin-bottom: 4px; color: #555; font-size: 0.95em; }
.paper-box-text .desc { font-size: 0.9em; margin: 6px 0 8px 0; color: #444; }
.paper-box-text .links a {
  margin-right: 10px;
  font-size: 0.9em;
  font-weight: 500;
  color: #0366d6;
  text-decoration: none;
}
.paper-box-text .links a:hover { text-decoration: underline; color: #005cc5; }
.badge {
  position: absolute; top: 6px; left: 6px;
  background: rgba(0, 0, 0, 0.72); color: #fff;
  padding: 2px 6px; border-radius: 4px; font-size: 0.75em;
  backdrop-filter: blur(4px);
}

/* Education & Experience Cards */
.exp-card {
  display: flex; align-items: flex-start;
  background: #fdfdfd; border: 1px solid #eaeaea;
  border-radius: 8px; padding: 16px; margin-bottom: 16px;
  transition: background-color 0.2s;
}
.exp-card:hover { background: #f8f9fa; }
.exp-logo {
  width: 72px;
  height: 72px;
  flex-shrink: 0;
  margin-right: 18px;
  border-radius: 4px;
  object-fit: contain;
}
.exp-content { flex-grow: 1; display: flex; flex-direction: column; justify-content: center; min-height: 72px; }
.exp-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 4px; }
.exp-role { font-weight: 600; font-size: 1.05em; color: #24292e; margin: 0; }
.exp-time { font-size: 0.9em; color: #586069; white-space: nowrap; }
.exp-org { font-weight: 500; color: #0366d6; font-size: 0.95em; margin-bottom: 6px; }
.exp-desc { font-size: 0.9em; color: #444; margin: 0; line-height: 1.5; }

/* Highlights & Collapsible */
.highlight-award { font-weight: 600; color: #b31b1b; background: #fff0f0; padding: 2px 6px; border-radius: 4px; }
.highlight-honor { font-weight: 600; color: #005cc5; background: #f0f8ff; padding: 2px 6px; border-radius: 4px; }

details.projects-section summary {
  cursor: pointer; font-weight: 600; font-size: 1.1em;
  color: #24292e; background: #f6f8fa; padding: 12px 16px;
  border-radius: 8px; border: 1px solid #eaeaea; outline: none;
  transition: background 0.2s; user-select: none;
}
details.projects-section summary:hover { background: #e1e4e8; }
details.projects-section[open] summary { margin-bottom: 20px; border-bottom-left-radius: 0; border-bottom-right-radius: 0; }
.zh-translation { font-size: 0.85em; color: #666; font-weight: normal; }
</style>

<!-- <span class="anchor" id="internships"></span>
# 💼 Internships

<div class="exp-card">
  <img src="{{ '/images/building-icon.svg' | relative_url }}" class="exp-logo" alt="Organization Placeholder">
  <div class="exp-content">
    <div class="exp-header">
      <h3 class="exp-role">Research Intern / Visiting Student</h3>
      <span class="exp-time">2025.01 - Present</span>
    </div>
    <div class="exp-org">Organization / Lab Name</div>
    <p class="exp-desc">Describe your internship or research role here. Summarize the type of work you do, the domain you contribute to, and the scope of your responsibilities.</p>
  </div>
</div> -->





<span class="anchor" id="publications"></span>
# 📝 Publications
<p style="font-size: 0.9em; color: #666; margin-top: -10px; margin-bottom: 20px;">
  (* Equal Contribution, † Corresponding Author)
</p>

<div class='paper-box'>
  <div class='paper-box-image'>
    <!-- <div class='badge'>Conference 2026</div> -->
    <img src="{{ '/images/sketchfluid.png' | relative_url }}" alt="Publication Placeholder">
  </div>
  <div class='paper-box-text'>
    <a href="https://www.sciencedirect.com/science/article/pii/S2095263526000452" class="title">Controllable Fluid Motion Synthesis with Video Diffusion Model</a>
    <div class="authors"><strong>Hao Jin</strong>, Hengyuan Chang, Zhengyang Wang, Shaojun Hu, Haoran Xie†</div>
    <div class="venue"><em><strong>Under review</strong></em></div>
    <!-- <p class="desc"><strong>TL;DR:</strong> Use this card for another representative paper or preprint you want to highlight.</p> -->
    <div class="links">
      <a href="https://www.sciencedirect.com/science/article/pii/S2095263526000452">[Paper]</a>
      <!-- <a href="#">[Code]</a>
      <a href="#">[Project Page]</a> -->
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <!-- <div class='badge'>Conference 2026</div> -->
    <img src="{{ '/images/sketch2cinemagraph.png' | relative_url }}" alt="Publication Placeholder">
  </div>
  <div class='paper-box-text'>
    <a href="https://www.sciencedirect.com/science/article/pii/S009784932600018X" class="title">Sketch-guided Stylized Landscape Cinemagraph Synthesis</a>
    <div class="authors"><strong>Hao Jin</strong>, Hengyuan Chang, Xiaoxuan Xie, Zhengyang Wang, Xusheng Du, Shaojun Hu, Haoran Xie†</div>
    <div class="venue"><em><strong>Computers & Graphics</strong>, 2026</em></div>
    <!-- <p class="desc"><strong>TL;DR:</strong> Add one sentence that explains the core idea, result, or contribution of the paper.</p> -->
    <div class="links">
      <a href="https://www.sciencedirect.com/science/article/pii/S009784932600018X">[Paper]</a>
      <!-- <a href="#">[Code]</a> -->
      <!-- <a href="#">[Project Page]</a> -->
      <!-- <a href="#">[Dataset]</a> -->
    </div>
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <!-- <div class='badge'>Conference 2026</div> -->
    <img src="{{ '/images/far26.png' | relative_url }}" alt="Publication Placeholder">
  </div>
  <div class='paper-box-text'>
    <a href="https://www.sciencedirect.com/science/article/pii/S2095263526000452" class="title">Controllable generation of building representations: Aligning campus building design intent with multi-stage retrieval-augmented diffusion models</a>
    <div class="authors">Zhengyang Wang*, Yuxiao Ren*, <strong>Hao Jin</strong>, Jieli Feng, Xusheng Du, Ye Zhang†, Haoran Xie†</div>
    <div class="venue"><em><strong>Frontiers of Architectural Research</strong>, 2026</em></div>
    <!-- <p class="desc"><strong>TL;DR:</strong> Use this card for another representative paper or preprint you want to highlight.</p> -->
    <div class="links">
      <a href="https://www.sciencedirect.com/science/article/pii/S2095263526000452">[Paper]</a>
      <!-- <a href="#">[Code]</a>
      <a href="#">[Project Page]</a> -->
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <!-- <div class='badge'>Workshop / arXiv</div> -->
    <img src="{{ '/images/srt26.png' | relative_url }}" alt="Publication Placeholder">
  </div>
  <div class='paper-box-text'>
    <a href="#" class="title">Simulation-Ready Tree: High-Quality Dynamic Tree Reconstruction from a Single RGB-D Sensor</a>
    <div class="authors"><strong>Hao Jin*</strong>, Mingxin Jiao*, Haoran Xie, Shaojun Hu†</div>
    <div class="venue"><em><strong>International Conference on Robotics and Automation(ICRA)</strong>, 2026</em></div>
    <!-- <p class="desc"><strong>TL;DR:</strong> Add a compact summary sentence that is easy to scan from the homepage.</p> -->
    <div class="links">
      <a href="#">[Paper]</a>
      <a href="#">[Code]</a>
      <!-- <a href="#">[Project Page]</a>
      <a href="#">[Demo]</a> -->
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <!-- <div class='badge'>Under Review</div> -->
    <img src="{{ '/images/asc25.png' | relative_url }}" alt="Publication Placeholder">
  </div>
  <div class='paper-box-text'>
    <a href="https://arxiv.org/abs/2503.03090" class="title">From Architectural Sketch to Conceptual Representation: Using Structure-aware Diffusion Model to Generate Renderings of School Buildings</a>
    <div class="authors">Zhengyang Wang, <strong>Hao Jin</strong>, Xusheng Du, Yuxiao Ren, Ye Zhang, Haoran Xie†</div>
    <div class="venue"><em><strong>The Association for Computer‑Aided Architectural Design Research in Asia (CAADRIA) 2025</strong></em></div>
    <!-- <p class="desc"><strong>TL;DR:</strong> This slot works well for a recent submission, preprint, or work-in-progress project.</p> -->
    <div class="links">
      <a href="https://arxiv.org/abs/2503.03090">[Paper]</a>
      <!-- <a href="#">[Code]</a>
      <a href="#">[Project Page]</a> -->
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <!-- <div class='badge'>Conference 2025</div> -->
    <img src="{{ '/images/oriental23.png' | relative_url }}" alt="Publication Placeholder">
  </div>
  <div class='paper-box-text'>
    <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10238803" class="title">A Semi-Automatic Oriental Ink Painting Framework for Robotic Drawing From 3D Models</a>
    <div class="authors"><strong>Hao Jin</strong>, Minghui Lian, Shicheng Qiu, Xuxu Han, Xizhi Zhao, Long Yang, Zhiyi Zhang, Haoran Xie, Kouichi Konno, Shaojun Hu†</div>
    <div class="venue">
      <em><strong> IEEE Robotics and Automation Letters</strong>, 2023</em><br>
      <!-- <strong style="color: #b31b1b;">🏆 Optional Highlighted Award or Distinction</strong> -->
    </div>
    <p class="desc">Oral in IEEE International Conference on Robotics and Automation(ICRA) 2024.</p>
    <div class="links">
      <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10238803">[Paper]</a>
      <!-- <a href="#">[Code]</a>
      <a href="#">[Project Page]</a>
      <a href="#">[Demo]</a> -->
    </div>
  </div>
</div>







