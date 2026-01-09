---
permalink: /tools/
title: "Skills & Tools"
author_profile: true
redirect_from: 
  - /tools.html
---
<!-- Programming Languages -->
<div class="skill-card">
  <div class="skill-header">
    <div class="skill-title">Programming Languages</div>
    <div class="skill-subtitle">Core coding stack</div>
  </div>
  <div class="skill-tags">
    <span class="skill-tag">Python</span>
    <span class="skill-tag">Python 3</span>
    <span class="skill-tag">C</span>
    <span class="skill-tag">C++</span>
    <span class="skill-tag">SQL</span>
    <span class="skill-tag">JavaScript</span>
    <span class="skill-tag">Java</span>
    <span class="skill-tag">MATLAB</span>
    <span class="skill-tag">Bash / Shell</span>
    <span class="skill-tag">HTML</span>
    <span class="skill-tag">CSS</span>
  </div>
</div>

<!-- Frameworks & Tools -->
<div class="skill-card">
  <div class="skill-header">
    <div class="skill-title">Frameworks & Developer Tools</div>
    <div class="skill-subtitle">Build · test · ship</div>
  </div>
  <div class="skill-tags">
    <span class="skill-tag">Git</span>
    <span class="skill-tag">Docker</span>
    <span class="skill-tag">AWS</span>
    <span class="skill-tag">React.js</span>
    <span class="skill-tag">React Native</span>
    <span class="skill-tag">Node.js</span>
    <span class="skill-tag">Bootstrap</span>
    <span class="skill-tag">Django</span>
    <span class="skill-tag">OpenCV</span>
    <span class="skill-tag">VS Code</span>
    <span class="skill-tag">Cursor</span>
  </div>
</div>

<!-- Databases & Data Processing -->
<div class="skill-card">
  <div class="skill-header">
    <div class="skill-title">Databases & Data Processing</div>
    <div class="skill-subtitle">Storage · analytics · ML</div>
  </div>
  <div class="skill-tags">
    <span class="skill-tag">MySQL</span>
    <span class="skill-tag">MongoDB</span>
    <span class="skill-tag">PostgreSQL</span>
    <span class="skill-tag">SQLite</span>
    <span class="skill-tag">Redis</span>
    <span class="skill-tag">Elasticsearch</span>
    <span class="skill-tag">NumPy</span>
    <span class="skill-tag">Pandas</span>
    <span class="skill-tag">scikit-learn</span>
  </div>
</div>

<!-- Machine Learning & Computer Vision -->
<div class="skill-card">
  <div class="skill-header">
    <div class="skill-title">Machine Learning & Computer Vision</div>
    <div class="skill-subtitle">Modeling · vision · inference</div>
  </div>
  <div class="skill-tags">
    <span class="skill-tag">PyTorch</span>
    <span class="skill-tag">TensorFlow</span>
    <span class="skill-tag">OpenCV</span>
    <span class="skill-tag">YOLO</span>
    <span class="skill-tag">ResNet</span>
    <span class="skill-tag">U-Net</span>
    <span class="skill-tag">ViT</span>
    <span class="skill-tag">3D Vision</span>
    <span class="skill-tag">Reconstruction</span>
  </div>
</div>

<!-- Systems & Infrastructure -->
<div class="skill-card">
  <div class="skill-header">
    <div class="skill-title">Systems & Infrastructure</div>
    <div class="skill-subtitle">Performance · reliability</div>
  </div>
  <div class="skill-tags">
    <span class="skill-tag">Kafka</span>
    <span class="skill-tag">Spark Streaming</span>
    <span class="skill-tag">NGINX</span>
    <span class="skill-tag">Redis</span>
    <span class="skill-tag">Linux</span>
    <span class="skill-tag">REST APIs</span>
  </div>
</div>


<style>
.skill-card {
  background: #ffffff;
  border-radius: 14px;
  padding: 18px 22px;
  margin-bottom: 24px;

  border: 2px solid rgba(0, 0, 0, 0.08);
  box-shadow:
    0 4px 8px rgba(0,0,0,0.08),
    0 10px 24px rgba(0,0,0,0.12);

  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
}

.skill-card:hover {
  transform: translateY(-3px);
  box-shadow:
    0 8px 16px rgba(0,0,0,0.12),
    0 16px 36px rgba(0,0,0,0.18);
  border-color: rgba(0,0,0,0.14);
}

.skill-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 16px;
  margin-bottom: 10px;
}

.skill-title {
  font-weight: 800;
  font-size: 1.05rem;
}

.skill-subtitle {
  color: #777;
  font-size: 0.9rem;
  white-space: nowrap;
}

.skill-tags {
  margin-top: 6px;
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.skill-tag {
  font-size: 0.88rem;
  color: #444;
  background: rgba(0,0,0,0.05);
  padding: 5px 10px;
  border-radius: 999px;
  border: 1px solid rgba(0,0,0,0.06);
}

.skill-notes {
  margin: 8px 0 0 0;
  padding-left: 18px;
}

.skill-notes li {
  margin-bottom: 6px;
  line-height: 1.5;
}

@media (max-width: 600px) {
  .skill-header {
    flex-direction: column;
    align-items: flex-start;
  }
  .skill-subtitle {
    white-space: normal;
  }
}
</style>