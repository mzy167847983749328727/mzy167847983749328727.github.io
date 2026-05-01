---
layout: archive
title: "Timeline"
permalink: /timeline/
author_profile: true
---

<style>
.timeline {
  position: relative;
  max-width: 900px;
  margin: 40px auto;
  padding: 20px 0;
}

.timeline::after {
  content: '';
  position: absolute;
  width: 4px;
  background: linear-gradient(#4f46e5, #06b6d4);
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -2px;
  border-radius: 2px;
}

.timeline-item {
  padding: 20px 40px;
  position: relative;
  width: 50%;
  opacity: 0;
  transform: translateY(40px);
  animation: fadeUp 0.8s ease forwards;
}

.timeline-item:nth-child(1) { animation-delay: 0.1s; }
.timeline-item:nth-child(2) { animation-delay: 0.3s; }
.timeline-item:nth-child(3) { animation-delay: 0.5s; }

.timeline-item.left { left: 0; }
.timeline-item.right { left: 50%; }

.timeline-item::after {
  content: '';
  position: absolute;
  width: 18px;
  height: 18px;
  right: -9px;
  background-color: white;
  border: 4px solid #4f46e5;
  top: 32px;
  border-radius: 50%;
  z-index: 1;
}

.timeline-item.right::after { left: -9px; }

.timeline-content {
  padding: 22px 26px;
  background: white;
  border-radius: 16px;
  box-shadow: 0 8px 24px rgba(0,0,0,0.12);
  transition: 0.3s;
  display: flex;
  gap: 15px;
  align-items: center;
}

.timeline-content:hover {
  transform: translateY(-6px);
  box-shadow: 0 14px 32px rgba(0,0,0,0.18);
}

.logo {
  width: 60px;
  height: 60px;
  object-fit: contain;
}

.text {
  flex: 1;
}

.timeline-date {
  font-weight: bold;
  color: #64748b;
}

.timeline-degree {
  font-weight: bold;
  margin: 5px 0;
}

@keyframes fadeUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@media screen and (max-width: 768px) {
  .timeline::after { left: 24px; }

  .timeline-item {
    width: 100%;
    padding-left: 60px;
  }

  .timeline-item.left,
  .timeline-item.right { left: 0; }

  .timeline-item::after,
  .timeline-item.right::after { left: 15px; }
}
</style>

<div class="timeline">

  <!-- 本科 -->
  <div class="timeline-item left">
    <div class="timeline-content">
      <img class="logo" src="https://upload.wikimedia.org/wikipedia/zh/thumb/0/0b/Hebei_University_logo.svg/120px-Hebei_University_logo.svg.png">
      <div class="text">
        <div class="timeline-date">2019 - 2023</div>
        <div class="timeline-degree">Undergraduate</div>
        <h3>河北大学 管理学院</h3>
      </div>
    </div>
  </div>

  <!-- 硕士 -->
  <div class="timeline-item right">
    <div class="timeline-content">
      <img class="logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/CAS_logo.svg/120px-CAS_logo.svg.png">
      <div class="text">
        <div class="timeline-date">2023 - 2026</div>
        <div class="timeline-degree">Master's</div>
        <h3>中国科学院 文献情报中心</h3>
      </div>
    </div>
  </div>

  <!-- 博士 -->
  <div class="timeline-item left">
    <div class="timeline-content">
      <img class="logo" src="https://upload.wikimedia.org/wikipedia/zh/thumb/1/1b/Wuhan_University_Logo.svg/120px-Wuhan_University_Logo.svg.png">
      <div class="text">
        <div class="timeline-date">2026 - Present</div>
        <div class="timeline-degree">PhD</div>
        <h3>武汉大学 信息管理学院</h3>
      </div>
    </div>
  </div>

</div>
