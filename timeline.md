---
layout: archive
title: "Timeline"
permalink: /timeline/
author_profile: true
---

<style>
.timeline-hero {
  text-align: center;
  padding: 45px 20px 25px;
}

.timeline-hero h1 {
  font-size: 42px;
  margin-bottom: 10px;
  background: linear-gradient(90deg, #2563eb, #06b6d4, #9333ea);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.timeline-hero p {
  color: #64748b;
  font-size: 17px;
}

.edu-timeline {
  position: relative;
  max-width: 980px;
  margin: 30px auto 70px;
  padding: 20px 0;
}

.edu-timeline::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 50%;
  width: 5px;
  transform: translateX(-50%);
  background: linear-gradient(180deg, #2563eb, #06b6d4, #9333ea);
  border-radius: 999px;
}

.edu-item {
  position: relative;
  width: 50%;
  padding: 28px 45px;
  opacity: 0;
  transform: translateY(50px);
  transition: all 0.8s ease;
}

.edu-item.show {
  opacity: 1;
  transform: translateY(0);
}

.edu-item.left {
  left: 0;
}

.edu-item.right {
  left: 50%;
}

.edu-dot {
  position: absolute;
  top: 45px;
  width: 22px;
  height: 22px;
  background: #ffffff;
  border: 5px solid #2563eb;
  border-radius: 50%;
  z-index: 2;
  box-shadow: 0 0 0 8px rgba(37, 99, 235, 0.12);
}

.edu-item.left .edu-dot {
  right: -11px;
}

.edu-item.right .edu-dot {
  left: -11px;
}

.edu-card {
  position: relative;
  padding: 26px;
  border-radius: 24px;
  background: rgba(255, 255, 255, 0.82);
  backdrop-filter: blur(12px);
  box-shadow: 0 16px 40px rgba(15, 23, 42, 0.12);
  border: 1px solid rgba(226, 232, 240, 0.8);
  transition: all 0.35s ease;
  overflow: hidden;
}

.edu-card::before {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, rgba(37,99,235,0.08), rgba(6,182,212,0.08), rgba(147,51,234,0.08));
  opacity: 0;
  transition: opacity 0.35s ease;
}

.edu-card:hover {
  transform: translateY(-8px) scale(1.015);
  box-shadow: 0 24px 55px rgba(15, 23, 42, 0.18);
}

.edu-card:hover::before {
  opacity: 1;
}

.edu-header {
  position: relative;
  display: flex;
  gap: 18px;
  align-items: center;
  z-index: 1;
}

.edu-logo {
  width: 76px;
  height: 76px;
  object-fit: contain;
  padding: 10px;
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.10);
}

.edu-year {
  display: inline-block;
  margin-bottom: 8px;
  padding: 5px 12px;
  border-radius: 999px;
  color: #ffffff;
  font-size: 13px;
  font-weight: 700;
  background: linear-gradient(90deg, #2563eb, #06b6d4);
}

.edu-degree {
  margin: 0;
  font-size: 22px;
  font-weight: 800;
  color: #0f172a;
}

.edu-school {
  margin: 6px 0 0;
  font-size: 16px;
  color: #334155;
  font-weight: 600;
}

.edu-detail {
  position: relative;
  z-index: 1;
  margin-top: 18px;
  color: #475569;
  line-height: 1.75;
}

.edu-tags {
  position: relative;
  z-index: 1;
  margin-top: 16px;
}

.edu-tags span {
  display: inline-block;
  margin: 4px 6px 4px 0;
  padding: 5px 10px;
  border-radius: 999px;
  background: #f1f5f9;
  color: #475569;
  font-size: 13px;
}

@media screen and (max-width: 768px) {
  .timeline-hero h1 {
    font-size: 34px;
  }

  .edu-timeline::before {
    left: 24px;
  }

  .edu-item,
  .edu-item.left,
  .edu-item.right {
    width: 100%;
    left: 0;
    padding: 24px 20px 24px 62px;
  }

  .edu-item.left .edu-dot,
  .edu-item.right .edu-dot {
    left: 13px;
  }

  .edu-header {
    align-items: flex-start;
  }

  .edu-logo {
    width: 62px;
    height: 62px;
  }
}
</style>

<div class="timeline-hero">
  <h1>Academic Timeline</h1>
  <p>My academic journey from undergraduate study to doctoral research.</p>
</div>

<div class="edu-timeline">

  <div class="edu-item left">
    <div class="edu-dot"></div>
    <div class="edu-card">
      <div class="edu-header">
        <img class="edu-logo" src="/images/hbu.png" alt="Hebei University logo">
        <div>
          <div class="edu-year">2019 - 2023</div>
          <h2 class="edu-degree">Undergraduate</h2>
          <p class="edu-school">河北大学 · 管理学院</p>
        </div>
      </div>
      <div class="edu-detail">
        本科阶段学习管理学与信息相关课程，奠定专业基础。
      </div>
      <div class="edu-tags">
        <span>Hebei University</span>
        <span>Management</span>
        <span>Undergraduate</span>
      </div>
    </div>
  </div>

  <div class="edu-item right">
    <div class="edu-dot"></div>
    <div class="edu-card">
      <div class="edu-header">
        <img class="edu-logo" src="/images/cas.png" alt="CAS logo">
        <div>
          <div class="edu-year">2023 - 2026</div>
          <h2 class="edu-degree">Master's Study</h2>
          <p class="edu-school">中国科学院文献情报中心</p>
        </div>
      </div>
      <div class="edu-detail">
        研究生阶段聚焦文献情报、信息资源管理与科研数据相关方向。
      </div>
      <div class="edu-tags">
        <span>CAS</span>
        <span>Library & Information Science</span>
        <span>Master</span>
      </div>
    </div>
  </div>

  <div class="edu-item left">
    <div class="edu-dot"></div>
    <div class="edu-card">
      <div class="edu-header">
        <img class="edu-logo" src="/images/whu.png" alt="Wuhan University logo">
        <div>
          <div class="edu-year">2026 - Present</div>
          <h2 class="edu-degree">PhD Study</h2>
          <p class="edu-school">武汉大学 · 信息管理学院</p>
        </div>
      </div>
      <div class="edu-detail">
        博士阶段将在信息管理、知识组织、数据治理或相关方向继续深入研究。
      </div>
      <div class="edu-tags">
        <span>Wuhan University</span>
        <span>Information Management</span>
        <span>PhD</span>
      </div>
    </div>
  </div>

</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const items = document.querySelectorAll(".edu-item");

  const observer = new IntersectionObserver(function (entries) {
    entries.forEach(function (entry) {
      if (entry.isIntersecting) {
        entry.target.classList.add("show");
      }
    });
  }, { threshold: 0.2 });

  items.forEach(function (item) {
    observer.observe(item);
  });
});
</script>
