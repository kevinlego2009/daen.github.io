---
permalink: /work/
title: "Work Experience"
author_profile: true
redirect_from: 
  - /work.html
---

<!-- Garena -->
<div class="work-card">
  <div class="work-header">
    <strong>Backend Engineer</strong>
    <span class="work-date">Jun 2024 – Aug 2024</span>
  </div>
  <div class="work-company">
    Garena Sea, Ltd.
    <span class="work-date" style="font-weight: normal">Taipei, Taiwan</span>
  </div>
  <ul class="work-points">
    <li>Designed and maintained RESTful APIs and backend services for analytics and data operations.</li>
    <li>Improved database performance and reliability using MySQL and MongoDB.</li>
    <li>Built a streaming data pipeline with Apache Kafka and Spark Streaming for low-latency analytics and ML workflows.</li>
    <li>Optimized service performance with Redis caching and NGINX load balancing.</li>
  </ul>
</div>

<!-- ASE -->
<div class="work-card">
  <div class="work-header">
    <strong>Customer Engineering Integration Engineer</strong>
    <span class="work-date">Oct 2020 – May 2023</span>
  </div>
  <div class="work-company">
    ASE (Advanced Semiconductor Engineering) Global Group
    <span class="work-date" style="font-weight: normal">Taoyuan, Taiwan</span>    
  </div>
  <ul class="work-points">
    <li>Led new product introduction (NPI) and ramp-to-mass-production support using SPC, DOE, and structured root-cause analysis.</li>
    <li>Built Python-based data processing tools (NumPy, Pandas) for large-scale semiconductor test data.</li>
    <li>Developed manufacturing quality monitoring and anomaly detection software using SVMs.</li>
    <li>Integrated data tooling into IC packaging and testing workflows to improve process visibility.</li>
  </ul>
</div>

<style>
.work-card {
  background: #ffffff;
  border-radius: 14px;
  padding: 18px 22px;
  margin-bottom: 24px;
  box-shadow: 0 6px 16px rgba(0,0,0,0.08);
  transition: transform .2s ease, box-shadow .2s ease;
  border: 2px solid rgba(0, 0, 0, 0.06);
  backdrop-filter: saturate(120%) blur(0.5px);
}

.work-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 22px rgba(0,0,0,0.12);
}

.work-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  font-size: 1.05rem;
  margin-bottom: 4px;
}

.work-date {
  font-size: 0.9rem;
  color: #777;
}

.work-company {
  font-weight: 600;
  margin-bottom: 10px;
  color: #444;
  display: flex;
  justify-content: space-between;
  align-items: baseline;
}

.work-points {
  padding-left: 18px;
  margin: 0;
}

.work-points li {
  margin-bottom: 6px;
  line-height: 1.5;
}
</style>
