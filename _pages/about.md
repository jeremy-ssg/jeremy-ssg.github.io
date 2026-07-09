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

# About Me

<p class="intro-line">
I am Gang Sun, a doctoral student in Artificial Intelligence at Dalian University of Technology. I work with the Intelligent Robot Lab on aerial robotics, motion planning, and perception-aware planning.
</p>

My current research focuses on enabling unmanned aerial vehicles to plan reliable trajectories while reasoning about sensing quality, localization uncertainty, and environmental structure. Before starting my doctoral study, I received the B.Eng. degree in Automation and the M.Eng. degree in Control Science and Engineering from Dalian University of Technology.

<span class='anchor' id='research'></span>

# Research Interests

<div class="research-tags">
  <span>Motion Planning</span>
  <span>Perception-Aware Planning</span>
  <span>Aerial Robotics</span>
  <span>Localization Uncertainty</span>
  <span>SLAM</span>
</div>

<span class='anchor' id='news'></span>

# News

- *2024.02*: One paper was accepted by IEEE Transactions on Intelligent Transportation Systems.

<span class='anchor' id='publications'></span>

# Publications

<div class="featured-publications">
  <article class="featured-paper">
    <figure class="featured-paper__image">
      <img src="{{ '/images/publications/orbit-planner.png' | relative_url }}" alt="Orbit Planner method overview">
    </figure>
    <div class="featured-paper__content">
      <h2><a href="{{ '/files/papers/orbit-planner.pdf' | relative_url }}">Orbit Planner: Obstacle Uncertainty-Aware and Probabilistic Cost-Weighted Trajectory Planner Under Perception-Limited Constraint</a></h2>
      <p class="paper-meta">IEEE Transactions on Aerospace and Electronic Systems, 2026</p>
      <p>
        Orbit Planner addresses UAV motion planning in environments where perception is limited and obstacle occupancy remains uncertain. The method introduces a probabilistic cost-weighted kinodynamic search that prefers free space while still allowing unknown space to be explored when necessary.
      </p>
      <p>
        It further generates conservative and aggressive trajectory candidates under obstacle uncertainty. A visibility-aware local state determination strategy is used to reduce flight risk as new observations refine the map.
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
        This work studies quadrotor trajectory planning that considers both flight safety and perception quality. The core idea is to actively plan the yaw trajectory so the robot can observe informative landmarks while maintaining safe flight.
      </p>
      <p>
        The planner combines a coarse-to-fine graph search with a yaw safety corridor and a map Fisher information field. A path-guided optimization stage then generates a safe and perception-aware trajectory for real-world execution.
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
        This paper proposes a real-time perception-aware receding horizon planning framework without relying on a pre-built global feature map. A memorable active map stores selected visual landmarks and supports online evaluation of candidate trajectories.
      </p>
      <p>
        The method generates topologically distinct position trajectories, evaluates them by perception quality, smoothness, collision possibility, and feasibility, and then plans a perception-aware yaw trajectory through graph search and trajectory optimization.
      </p>
      <p class="paper-actions"><a href="{{ '/files/papers/topology-guided-perception-aware-planning.pdf' | relative_url }}"><i class="fas fa-file-pdf"></i> PDF</a></p>
    </div>
  </article>
</div>

## Full Publication List

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

# Honors and Awards

<ul class="honor-list">
  <li><strong>2025.01</strong> Outstanding Master's Thesis of Liaoning Province.</li>
  <li><strong>2024.08</strong> Third Place in the Laser Season of the 2024 China SLAM Technology Challenge.</li>
  <li><strong>2024.06</strong> Outstanding Master's Graduate of Liaoning Province.</li>
  <li><strong>2023.08</strong> Champion of the Unmanned Collaborative Systems Track at the 25th China Robotics and Artificial Intelligence Competition.</li>
  <li><strong>2023.08</strong> Second Prize at the 1st Yixian Warriors Cup International Robotics Invitational Tournament.</li>
  <li><strong>2021.10</strong> First Prize at the 3rd Liaoning Province Artificial Intelligence Application Competition.</li>
  <li><strong>2021.06 / 2024.06</strong> Outstanding Graduate and Outstanding Postgraduate of Dalian University of Technology.</li>
  <li><strong>2020.03</strong> Honorable Mention in the Mathematical Contest in Modeling.</li>
  <li><strong>2019.12</strong> National Second Prize in the Higher Education Cup National College Student Mathematical Modeling Competition.</li>
</ul>

<span class='anchor' id='education'></span>

# Education

- *2024.09 - Present*, Doctor of Engineering in Artificial Intelligence, Dalian University of Technology.
- *2021.09 - 2024.06*, M.Eng. in Control Science and Engineering, Dalian University of Technology.
- *2017.09 - 2021.06*, B.Eng. in Automation, Dalian University of Technology.
