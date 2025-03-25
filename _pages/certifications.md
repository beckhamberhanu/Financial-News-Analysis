---
layout: archive
title: "Certifications"
permalink: /certifications/
author_profile: true
---

{% include base_path %}

<!-- Professional Certifications -->
<div class="grid__wrapper">
  <div class="archive__item">
    <h2 class="archive__item-title">Professional Certifications</h2>
    
    <div class="archive__item-excerpt">
      <div class="certification">
        <details class="certification-details">
          <summary>Project Management Professional (PMP®)</summary>
          <div class="certification-content">
            <p><strong>Issuing Organization:</strong> Project Management Institute (PMI)</p>
            <p><strong>Credential ID:</strong> [Your PMP Number]</p>
            <p><strong>Date Earned:</strong> [Month Year]</p>
            <p><strong>Status:</strong> Active</p>
            <p><a href="https://www.pmi.org/certifications/certification-resources/registry" target="_blank" rel="noopener noreferrer">Verify Credential</a></p>
          </div>
        </details>
      </div>

      <div class="certification">
        <details class="certification-details">
          <summary>Google Project Management Professional Certificate</summary>
          <div class="certification-content">
            <p><strong>Issuing Organization:</strong> Google via Coursera</p>
            <p><strong>Date Earned:</strong> [Month Year]</p>
            <p><strong>Credential ID:</strong> [Your Credential ID]</p>
            <p><a href="https://www.coursera.org/account/accomplishments" target="_blank" rel="noopener noreferrer">Verify Credential</a></p>
          </div>
        </details>
      </div>
    </div>
  </div>

  <!-- IT Certifications -->
  <div class="archive__item">
    <h2 class="archive__item-title">IT Certifications</h2>
    
    <div class="archive__item-excerpt">
      <div class="certification">
        <details class="certification-details">
          <summary>Linux Administration Bootcamp</summary>
          <div class="certification-content">
            <p><strong>Issuing Organization:</strong> [Platform Name]</p>
            <p><strong>Date Completed:</strong> [Month Year]</p>
            <p><strong>Certificate ID:</strong> [Your Certificate ID]</p>
          </div>
        </details>
      </div>

      <div class="certification">
        <details class="certification-details">
          <summary>Cisco Certified Network Associate (CCNAv7)</summary>
          <div class="certification-content">
            <p><strong>Issuing Organization:</strong> Cisco</p>
            <p><strong>Credential ID:</strong> [Your CCNA Number]</p>
            <p><strong>Date Earned:</strong> [Month Year]</p>
            <p><strong>Status:</strong> Active</p>
            <p><a href="https://www.cisco.com/c/en/us/training-events/training-certifications/certifications.html" target="_blank" rel="noopener noreferrer">Verify Credential</a></p>
          </div>
        </details>
      </div>

      <div class="certification">
        <details class="certification-details">
          <summary>Google IT Support Professional Certificate</summary>
          <div class="certification-content">
            <p><strong>Issuing Organization:</strong> Google via Coursera</p>
            <p><strong>Date Earned:</strong> [Month Year]</p>
            <p><strong>Credential ID:</strong> [Your Credential ID]</p>
            <p><a href="https://www.coursera.org/account/accomplishments" target="_blank" rel="noopener noreferrer">Verify Credential</a></p>
          </div>
        </details>
      </div>
    </div>
  </div>
</div>

<style>
.certification {
  margin-bottom: 1em;
  background-color: #f8f9fa;
}

.certification-details {
  width: 100%;
}

.certification-details summary {
  padding: 1em;
  cursor: pointer;
  font-size: 1em;
  font-weight: bold;
  color: #2980b9;
  border-left: 3px solid #2980b9;
  background-color: #f8f9fa;
  transition: all 0.3s ease;
}

.certification-details summary:hover {
  background-color: #eef2f5;
}

.certification-content {
  padding: 1em;
  border-left: 3px solid #2980b9;
  margin-top: 2px;
}

.certification-content p {
  margin: 0.5em 0;
}

.archive__item-title {
  margin-top: 1.5em;
  padding-bottom: 0.5em;
  border-bottom: 1px solid #f2f3f3;
}

/* Remove default details marker */
.certification-details > summary {
  list-style: none;
}

.certification-details > summary::-webkit-details-marker {
  display: none;
}

/* Add custom expand/collapse indicator */
.certification-details > summary::after {
  content: '+';
  float: right;
  font-size: 1.5em;
  line-height: 0.8;
  color: #2980b9;
}

.certification-details[open] > summary::after {
  content: '−';
}
</style>
