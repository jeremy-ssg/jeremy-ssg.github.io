---
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
---

<span class='anchor' id='about-me'></span>

<p class="language-switch"><a href="{{ '/' | relative_url }}">English</a></p>

# 个人简介

<p class="intro-line">
我是孙刚，目前在大连理工大学攻读人工智能专业工程博士学位，所在团队为大连理工大学智能机器人实验室。我的研究方向包括空中机器人、运动规划和感知约束下的轨迹规划。
</p>

我的研究主要关注无人机在复杂环境中的自主飞行问题，目标是让无人机在规划可靠轨迹的同时，主动考虑感知质量、定位不确定性和环境结构信息。在攻读博士学位之前，我于大连理工大学获得自动化专业工学学士学位和控制科学与工程专业工学硕士学位。

<span class='anchor' id='research'></span>

# 研究方向

<div class="research-tags">
  <span>运动规划</span>
  <span>感知驱动规划</span>
  <span>空中机器人</span>
  <span>定位不确定性</span>
  <span>SLAM</span>
</div>

<span class='anchor' id='news'></span>

# 新闻动态

- *2025.11*: 入选中国科协青年科技人才培育博士生专项计划。
- *2024.02*: 一篇论文被 IEEE Transactions on Intelligent Transportation Systems 接收。

<span class='anchor' id='publications'></span>

# 论文发表

<div class="featured-publications">
  <article class="featured-paper">
    <figure class="featured-paper__image">
      <img src="{{ '/images/publications/orbit-planner.png' | relative_url }}" alt="Orbit Planner method overview">
    </figure>
    <div class="featured-paper__content">
      <h2><a href="{{ '/files/papers/orbit-planner.pdf' | relative_url }}">Orbit Planner: Obstacle Uncertainty-Aware and Probabilistic Cost-Weighted Trajectory Planner Under Perception-Limited Constraint</a></h2>
      <p class="paper-meta">IEEE Transactions on Aerospace and Electronic Systems, 2026</p>
      <p>
        Orbit Planner 面向感知范围受限条件下的无人机运动规划问题，重点考虑未知空间中的障碍物占据不确定性。该方法提出了一种概率代价加权的动力学路径搜索策略，优先在已知自由空间中搜索轨迹，同时在必要时允许利用未知空间提高规划成功率。
      </p>
      <p>
        在轨迹生成阶段，方法同时生成保守的安全引导轨迹和更积极的目标引导轨迹，并通过可见性感知的局部状态判断策略，随着新观测不断更新环境信息，从而降低未知障碍物带来的飞行风险。
      </p>
      <p class="paper-actions"><a href="{{ '/files/papers/orbit-planner.pdf' | relative_url }}"><i class="fas fa-file-pdf"></i> PDF</a></p>
    </div>
  </article>

  <article class="featured-paper">
    <figure class="featured-paper__image">
      <img src="{{ '/images/publications/safety-driven-perception-aware-planning.png' | relative_url }}" alt="Safety-driven perception-aware trajectory planning framework">
    </figure>
    <div class="featured-paper__content">
      <h2><a href="{{ '/files/papers/safety-driven-perception-aware-planning.pdf' | relative_url }}">Safety-Driven and Localization Uncertainty-Driven Perception-Aware Trajectory Planning for Quadrotor Unmanned Aerial Vehicles</a></h2>
      <p class="paper-meta">IEEE Transactions on Intelligent Transportation Systems, 2024</p>
      <p>
        该工作研究同时考虑飞行安全和感知质量的四旋翼无人机轨迹规划问题。核心思想是在规划位置轨迹的基础上主动规划偏航角轨迹，使无人机在安全飞行的同时尽可能观测到更有利于定位的环境特征。
      </p>
      <p>
        方法结合粗到细图搜索、偏航安全走廊和地图 Fisher 信息场，对候选偏航路径进行安全性和感知质量评估；随后通过路径引导的轨迹优化生成可执行的安全感知轨迹。
      </p>
      <p class="paper-actions"><a href="{{ '/files/papers/safety-driven-perception-aware-planning.pdf' | relative_url }}"><i class="fas fa-file-pdf"></i> PDF</a></p>
    </div>
  </article>

  <article class="featured-paper">
    <figure class="featured-paper__image">
      <img src="{{ '/images/publications/topology-guided-perception-aware-planning.png' | relative_url }}" alt="Topology-guided perception-aware trajectory generation pipeline">
    </figure>
    <div class="featured-paper__content">
      <h2><a href="{{ '/files/papers/topology-guided-perception-aware-planning.pdf' | relative_url }}">Topology-Guided Perception-Aware Receding Horizon Trajectory Generation for UAVs</a></h2>
      <p class="paper-meta">IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2023</p>
      <p>
        该论文提出了一种实时感知驱动的滚动时域轨迹生成方法，不依赖预先构建的全局特征地图。方法通过可记忆主动地图选择性保存视觉路标，并利用该地图在线评估候选轨迹的感知质量。
      </p>
      <p>
        该方法首先生成具有不同拓扑结构的位置轨迹，并从感知质量、平滑性、碰撞可能性和可行性等方面进行评价；随后通过前端图搜索和后端轨迹优化生成感知驱动的偏航角轨迹。
      </p>
      <p class="paper-actions"><a href="{{ '/files/papers/topology-guided-perception-aware-planning.pdf' | relative_url }}"><i class="fas fa-file-pdf"></i> PDF</a></p>
    </div>
  </article>
</div>

## 完整论文列表

<ol class="publication-list">
  <li>
    <strong>G. Sun</strong>, X. Zhang, Y. Liu, X. Zhang, and Y. Zhuang,
    "Orbit Planner: Obstacle Uncertainty-Aware and Probabilistic Cost-Weighted Trajectory Planner Under Perception-Limited Constraint,"
    <em>IEEE Transactions on Aerospace and Electronic Systems</em>, vol. 62, 2026.
  </li>
  <li>
    <strong>G. Sun</strong>, X. Zhang, Y. Liu, X. Zhang, and Y. Zhuang,
    "Safety-Driven and Localization Uncertainty-Driven Perception-Aware Trajectory Planning for Quadrotor Unmanned Aerial Vehicles,"
    <em>IEEE Transactions on Intelligent Transportation Systems</em>, vol. 25, no. 8, 2024.
  </li>
  <li>
    <strong>G. Sun</strong>, X. Zhang, Y. Liu, H. Wang, X. Zhang, and Y. Zhuang,
    "Topology-Guided Perception-Aware Receding Horizon Trajectory Generation for UAVs,"
    in Proc. <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</em>, 2023.
  </li>
  <li>
    <strong>G. Sun</strong>, X. Zhang, Y. Liu, H. Wang, and Y. Zhuang,
    "Active Informative Receding Horizon Planning for Quadrotors,"
    in Proc. <em>42nd Chinese Control Conference (CCC)</em>, 2023.
  </li>
  <li>
    X. Zhang, <strong>G. Sun</strong>, S. Lin, Y. Liu, X. Zhang, and Y. Zhuang,
    "TDHVIO: A Texture Richness Guided Double-Hybrid Visual-Inertial Odometry,"
    <em>IEEE Sensors Journal</em>, vol. 26, no. 10, 2026.
  </li>
  <li>
    H. Yao, X. Zhang, <strong>G. Sun</strong>, Y. Liu, and Y. Zhuang,
    "GIF-LIO: Geometry-Intensity Fused LiDAR-Inertial Odometry With Degeneracy-Constrained State Estimation,"
    <em>IEEE Transactions on Instrumentation and Measurement</em>, vol. 75, 2026.
  </li>
  <li>
    C. Zhang, X. Zhang, <strong>G. Sun</strong>, Y. Liu, and Y. Zhuang,
    "Lite-Tracker: A Lightweight Tracking Flight Planner Considering Environmental Topology,"
    <em>IEEE Transactions on Industrial Electronics</em>, vol. 73, no. 6, 2026.
  </li>
  <li>
    Y. Hou, X. Zhang, <strong>G. Sun</strong>, Y. Liu, and Y. Zhuang,
    "Decentralized Competition on Multi-Resolution Roadmaps for Efficient Multi-UAV Exploration in Large-Scale Unknown Environments,"
    <em>IEEE Transactions on Industrial Informatics</em>, accepted, 2026.
  </li>
  <li>
    J. Jiang, X. Zhang, <strong>G. Sun</strong>, Y. Liu, X. Zhang, and Y. Zhuang,
    "CLID-SLAM: A Coupled LiDAR-Inertial Neural Implicit Dense SLAM With Region-Specific SDF Estimation,"
    <em>IEEE Robotics and Automation Letters</em>, vol. 10, no. 4, 2025.
  </li>
  <li>
    H. Wang, X. Zhang, Y. Liu, <strong>G. Sun</strong>, X. Zhang, and Y. Zhuang,
    "PCDCT: Perception-Complementarity-Driven Collaborative Trajectory Generation for Vision-Based Aerial Tracking,"
    <em>IEEE Transactions on Automation Science and Engineering</em>, vol. 22, 2025.
  </li>
  <li>
    H. Yao, X. Zhang, <strong>G. Sun</strong>, Y. Liu, X. Zhang, and Y. Zhuang,
    "MUP-LIO: Mapping Uncertainty-aware Point-wise Lidar Inertial Odometry,"
    in Proc. <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</em>, 2024.
  </li>
  <li>
    S. Guo, X. Zhang, H. Wang, <strong>G. Sun</strong>, Y. Liu, and Y. Zhuang,
    "A Multi-UAV Monitoring and Search Strategy Based on Multi-Agent Reinforcement Learning,"
    in Proc. <em>IEEE International Conference on Unmanned Systems (ICUS)</em>, 2024.
  </li>
</ol>

<span class='anchor' id='honors'></span>

# 荣誉奖励

<ul class="honor-list">
  <li><strong>2025.11</strong> 入选中国科协青年科技人才培育博士生专项计划。</li>
  <li><strong>2025.01</strong> 辽宁省优秀硕士学位论文。</li>
  <li><strong>2024.08</strong> 2024 中国 SLAM 技术挑战赛激光雷达赛季第三名。</li>
  <li><strong>2024.06</strong> 辽宁省优秀硕士毕业生。</li>
  <li><strong>2023.08</strong> 第二十五届中国机器人及人工智能大赛无人协同系统赛道冠军。</li>
  <li><strong>2023.08</strong> 首届“逸仙勇士杯”国际机器人邀请赛二等奖。</li>
  <li><strong>2021.10</strong> 第三届辽宁省人工智能应用大赛一等奖。</li>
  <li><strong>2021.06 / 2024.06</strong> 大连理工大学优秀毕业生、优秀研究生毕业生。</li>
  <li><strong>2020.03</strong> 美国大学生数学建模竞赛 Honorable Mention。</li>
  <li><strong>2019.12</strong> 高教社杯全国大学生数学建模竞赛国家二等奖。</li>
</ul>

<span class='anchor' id='education'></span>

# 教育经历

- *2024.09 - 至今*，大连理工大学，人工智能专业，工程博士。
- *2021.09 - 2024.06*，大连理工大学，控制科学与工程专业，工学硕士。
- *2017.09 - 2021.06*，大连理工大学，自动化专业，工学学士。
