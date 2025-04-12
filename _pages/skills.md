---
layout: archive
title: "Skills"
permalink: /skills/
author_profile: true
---

{% include base_path %}

<div class="grid__wrapper">
  <!-- Technical Skills -->
  <div class="archive__item">
    <h3>Technical Skills</h3>
    <div class="archive__item-excerpt">
      <div class="skills-section">
        <details class="skill-details">
          <summary class="skill-summary">Development & Project Management</summary>
          <div class="skill-content">
            <div class="skill-item">
              <span class="skill-name">Scrum</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 90%;"></div>
              </div>
              <span class="skill-level">Advanced</span>
            </div>
            <div class="skill-item">
              <span class="skill-name">SDLC</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 90%;"></div>
              </div>
              <span class="skill-level">Advanced</span>
            </div>
            <div class="skill-item">
              <span class="skill-name">Jira</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 70%;"></div>
              </div>
              <span class="skill-level">Intermediate</span>
            </div>
          </div>
        </details>

        <details class="skill-details">
          <summary class="skill-summary">Programming & Databases</summary>
          <div class="skill-content">
            <div class="skill-item">
              <span class="skill-name">Python</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 70%;"></div>
              </div>
              <span class="skill-level">Intermediate</span>
            </div>
            <div class="skill-item">
              <span class="skill-name">SQL</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 70%;"></div>
              </div>
              <span class="skill-level">Intermediate</span>
            </div>
            <div class="skill-item">
              <span class="skill-name">PHP</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 30%;"></div>
              </div>
              <span class="skill-level">Beginner</span>
            </div>
          </div>
        </details>

        <details class="skill-details">
          <summary class="skill-summary">Systems & Infrastructure</summary>
          <div class="skill-content">
            <div class="skill-item">
              <span class="skill-name">Linux</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 90%;"></div>
              </div>
              <span class="skill-level">Advanced</span>
            </div>
            <div class="skill-item">
              <span class="skill-name">Ubuntu</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 90%;"></div>
              </div>
              <span class="skill-level">Advanced</span>
            </div>
          </div>
        </details>
      </div>
    </div>
  </div>

  <!-- Project Management Skills -->
  <div class="archive__item">
    <h3>Project Management Skills</h3>
    <div class="archive__item-excerpt">
      <div class="skills-section">
        <details class="skill-details">
          <summary class="skill-summary">Management & Leadership</summary>
          <div class="skill-content">
            <div class="skill-item">
              <span class="skill-name">Agile Methodologies</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 90%;"></div>
              </div>
              <span class="skill-level">Advanced</span>
            </div>
            <div class="skill-item">
              <span class="skill-name">Stakeholder Management</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 90%;"></div>
              </div>
              <span class="skill-level">Advanced</span>
            </div>
          </div>
        </details>
      </div>
    </div>
  </div>

  <!-- Languages -->
  <div class="archive__item">
    <h3>Languages</h3>
    <div class="archive__item-excerpt">
      <div class="skills-section">
        <details class="skill-details">
          <summary class="skill-summary">Language Proficiency</summary>
          <div class="skill-content">
            <div class="skill-item">
              <span class="skill-name">English</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 100%;"></div>
              </div>
              <span class="skill-level">Native</span>
            </div>
            <div class="skill-item">
              <span class="skill-name">Amharic</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 95%;"></div>
              </div>
              <span class="skill-level">Fluent</span>
            </div>
            <div class="skill-item">
              <span class="skill-name">Afaan Oromo</span>
              <div class="skill-bar-container">
                <div class="skill-bar" style="width: 60%;"></div>
              </div>
              <span class="skill-level">Conversational</span>
            </div>
          </div>
        </details>
      </div>
    </div>
  </div>
</div>

<style>
.skills-section {
  margin-bottom: 20px;
  background-color: #f8f9fa;
}

.skill-details {
  width: 100%;
  margin-bottom: 15px;
}

.skill-summary {
  padding: 15px;
  cursor: pointer;
  font-weight: bold;
  color: #2980b9;
  border-left: 3px solid #2980b9;
  background-color: #f8f9fa;
  transition: all 0.3s ease;
}

.skill-summary:hover {
  background-color: #eef2f5;
}

.skill-content {
  padding: 15px;
  border-left: 3px solid #2980b9;
  margin-top: 2px;
}

.skill-item {
  display: flex;
  align-items: center;
  margin-bottom: 15px;
}

.skill-name {
  flex-basis: 200px;
  margin-right: 15px;
}

.skill-bar-container {
  flex-grow: 1;
  background-color: #f0f0f0;
  border-radius: 5px;
  height: 10px;
  overflow: hidden;
}

.skill-bar {
  background-color: #2980b9;
  height: 100%;
  border-radius: 5px;
}

.skill-level {
  margin-left: 15px;
  min-width: 100px;
  color: #666;
}

/* Remove default details marker */
.skill-details > summary {
  list-style: none;
}

.skill-details > summary::-webkit-details-marker {
  display: none;
}

/* Add custom expand/collapse indicator */
.skill-details > summary::after {
  content: '+';
  float: right;
  font-size: 1.5em;
  line-height: 1;
  color: #2980b9;
}

.skill-details[open] > summary::after {
  content: '−';
}

h3 {
  font-size: 1.5em;
  margin-bottom: 20px;
  color: #333;
}
</style>