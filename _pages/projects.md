---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from: 
  - /projects.html
---

<div class="project-card">
  <div class="project-header">
    <div class="project-title">Monocular to Stereo Video Reconstruction — AI/ML</div>
    <div class="project-meta">Jan 2025 – May 2025</div>
  </div>
  <div class="project-subtitle">Dynamic 4D reconstruction from monocular video</div>
  <ul class="project-points">
    <li>Curated a 4D dataset by fusing camera pose, disparity-based depth, and temporal tracking into dynamic point-cloud reconstructions.</li>
    <li>Improved reconstruction stability using trajectory smoothing and SIFT mismatch rejection.</li>
    <li>Extended DUSt3R with a ViT encoder and cross-attention decoder to predict time-aligned point clouds and scene flow.</li>
  </ul>
  <div class="tags">
    <span class="tag">Python</span>
    <span class="tag">4D Reconstruction</span>
    <span class="tag">SfM</span>
    <span class="tag">DUSt3R</span>
    <span class="tag">ViT</span>
    <span class="tag">SIFT</span>
    <span class="tag">Transformer</span>
  </div>
</div>

<div class="project-card">
  <div class="project-header">
    <div class="project-title">Lung Nodule Detector — AI/ML</div>
    <div class="project-meta">Jan 2025 – Apr 2025</div>
  </div>
  <div class="project-subtitle">CT classification + segmentation pipeline</div>
  <ul class="project-points">
    <li>Fine-tuned a ResNet model on lung CT scans, achieving 93.8% accuracy on nodule identification.</li>
    <li>Implemented a U-Net-based segmentation pipeline for precise lung nodule localization.</li>
    <li>Reduced false positives from 20% to 7% using a CNN-based nodule classifier.</li>
  </ul>
  <div class="tags">
    <span class="tag">Python</span>
    <span class="tag">ResNet</span>
    <span class="tag">U-Net</span>
    <span class="tag">Medical Imaging</span>
  </div>
</div>

<div class="project-card">
  <div class="project-header">
    <div class="project-title">Real-Time Eye Detector — AI/ML</div>
    <div class="project-meta">Sep 2024 – Jan 2025</div>
  </div>
  <div class="project-subtitle">YOLO-based eye detection + drowsiness signal</div>
  <ul class="project-points">
    <li>Applied transfer learning with YOLO for real-time face and eye detection.</li>
    <li>Integrated OpenCV and PyTorch for eye-state classification and drowsiness detection.</li>
    <li>Optimized inference performance; achieved mAP@0.5 = 0.98 on a custom dataset.</li>
  </ul>
  <div class="tags">
    <span class="tag">Python</span>
    <span class="tag">YOLO</span>
    <span class="tag">OpenCV</span>
    <span class="tag">PyTorch</span>
    <span class="tag">Real-time</span>
    <span class="tag">Custom dataset</span>
  </div>
</div>

<div class="project-card">
  <div class="project-header">
    <div class="project-title">Learning Management System — Full-Stack Web App</div>
    <div class="project-meta">Sep 2024 – Dec 2024</div>
  </div>

  <div class="project-subtitle">
    MERN-like platform featuring authentication, role-based access control, admin dashboards, and rich content editors.
    <!-- ·
    <a href="https://github.com/kevinlego2009/kanbas-react-web-app-cs5610-fa24/tree/a6" target="_blank" rel="noopener">Frontend</a>
    ·
    <a href="https://github.com/kevinlego2009/kanbas-node-server-app-cs5610-fa24/tree/quiz" target="_blank" rel="noopener">Backend</a> -->
  </div>

  <ul class="project-points">
    <li>Built a full-stack learning management system with user authentication (sign-up, login, logout) and role-based access control for admins, instructors, and students.</li>
    <li>Designed an admin system to manage users, courses, and enrollments, enabling end-to-end platform governance.</li>
    <li>Implemented a rich editor system for quizzes and assignments, supporting multiple question types and real-time form validation.</li>
    <li>Developed RESTful APIs and data models for core entities (users, courses, quizzes, questions), including cascading deletes and data integrity checks.</li>
    <li>Focused on building a complete application ecosystem with clean state management on the frontend and maintainable service-layer architecture on the backend.</li>
  </ul>

  <div class="tags">
    <span class="tag">React</span>
    <span class="tag">TypeScript</span>
    <span class="tag">Node.js</span>
    <span class="tag">Express</span>
    <span class="tag">MongoDB</span>
    <span class="tag">TypeScript</span>
    <span class="tag">Authentication</span>
    <span class="tag">RBAC</span>
    <span class="tag">Admin Dashboard</span>
  </div>
</div>



<div class="project-card">
  <div class="project-header">
    <div class="project-title">Real-Time Multiplayer Mobile Game</div>
    <div class="project-meta">Jun 2024 – Aug 2024</div>
  </div>

  <div class="project-subtitle">
    Android multiplayer strategy game powered by Firebase
    <!-- ·
    <a href="https://github.com/CS5520Summer2024Feinberg/final-project-finalproject-group11" target="_blank" rel="noopener">GitHub</a> -->
  </div>

  <ul class="project-points">
    <li>Developed a mine-detecting multiplayer game with real-time state sync for player actions and game events using Firebase.</li>
    <li>Implemented secure authentication and user data handling via Firebase login, plus player profiles tracking wins/losses and rates.</li>
    <li>Added interactive tutorials and adjustable settings (e.g., audio/notifications) to improve onboarding and usability.</li>
    <li>Collaborated in a team setting and shipped a working end-to-end mobile experience, including a published video tour.</li>
  </ul>

  <div class="tags">
    <span class="tag">Android</span>
    <span class="tag">Java</span>
    <span class="tag">Firebase</span>
    <span class="tag">Realtime Multiplayer</span>
    <span class="tag">Authentication</span>
    <span class="tag">UI/UX</span>
  </div>
</div>


<style>
.project-card {
  background: #ffffff;
  border-radius: 14px;
  padding: 18px 22px;
  margin-bottom: 24px;
  box-shadow: 0 6px 16px rgba(0,0,0,0.08);
  transition: transform .2s ease, box-shadow .2s ease;
  border: 2px solid rgba(0, 0, 0, 0.06);
  backdrop-filter: saturate(120%) blur(0.5px);
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 22px rgba(0,0,0,0.12);
}

.project-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 16px;
  margin-bottom: 8px;
}

.project-title {
  font-weight: 700;
  font-size: 1.05rem;
}

.project-meta {
  font-size: 0.9rem;
  color: #777;
  text-align: right;
  white-space: nowrap;
}

.project-subtitle {
  font-weight: 600;
  color: #444;
  margin-bottom: 10px;
}

.project-points {
  padding-left: 18px;
  margin: 0;
}

.project-points li {
  margin-bottom: 6px;
  line-height: 1.5;
}

.tags {
  margin-top: 12px;
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.tag {
  font-size: 0.85rem;
  color: #555;
  background: rgba(0,0,0,0.05);
  padding: 4px 10px;
  border-radius: 999px;
}

@media (max-width: 600px) {
  .project-header {
    flex-direction: column;
    align-items: flex-start;
  }
  .project-meta {
    text-align: left;
    white-space: normal;
  }
}
</style>