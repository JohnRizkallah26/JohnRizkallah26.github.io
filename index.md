---
layout: default
title: Home
---

# Welcome to My Site

<nav class="dropdown-nav">
  <details>
    <summary>👤 About</summary>
    <div class="dropdown-content">
      Hey everyone! I am originally from Rochester, NY & graduated from Brockport High School.  
      I enlisted in the Navy in 2017 as an Operations Specialist. I spent 3 years abroad in Rota, Spain.  
      This experience heavily shaped me as it forced me out of my comfort zone. I made hundreds of friends and gained valuable experience with computer systems.  
      However, I also made hundreds of mistakes, which I am extremely grateful for as it molded me into a better human.  
      I have lived in Florida since 2021, and will be leaving the Navy in 2026.
    </div>
  </details>

  <details>
    <summary>💻 Projects</summary>
    <div class="dropdown-content">
      Showcase your GitHub repositories, portfolio, or case studies.
    </div>
  </details>

  <details>
    <summary>✍️ Education/Credentials</summary>
    <div class="dropdown-content">
      Security + (Expires in 2028)<br>
      B.S in Cybersecurity<br>
      Google Cybersecurity Certificate<br>
      Secret Clearance
    </div>
  </details>

  <details>
    <summary>📚 Helpful Publications</summary>
    <div class="dropdown-content">
      <a href="https://www.nist.gov" target="_blank">Visit NIST Website</a>
    </div>
  </details>
</nav>

---

<div class="image-gallery">
  <img src="https://images.unsplash.com/photo-1519052537078-e6a6c1f1b2b4?q=80&auto=format&fit=crop&w=1200" alt="Maine Coon Kitten" />
</div>

<style>
/* Navigation container */
.dropdown-nav {
  display: flex;
  flex-direction: column;
  gap: 10px;
  background: #2c2c2c;
  padding: 15px;
  border-radius: 6px;
  max-width: 600px;
  margin: auto;
}

/* Summary acts like a button */
.dropdown-nav summary {
  cursor: pointer;
  font-weight: bold;
  padding: 10px;
  background: #444;
  color: #3b82f6;
  border-radius: 6px;
  list-style: none;
}

/* Remove default arrow */
.dropdown-nav summary::-webkit-details-marker {
  display: none;
}

/* Hover effect */
.dropdown-nav summary:hover {
  background: #555;
  color: #1d4ed8;
}

/* Content styling */
.dropdown-content {
  margin-top: 8px;
  padding: 10px;
  background: #e6e6e6;
  color: #3b82f6;
  border: 1px solid #888;
  border-radius: 6px;
}

/* Image gallery styling */
.image-gallery {
  display: flex;
  justify-content: center;
  margin-top: 30px;
}

.image-gallery img {
  max-width: 800px; /* bigger image */
  width: 100%;
  height: auto;
  border-radius: 12px;
  border: 3px solid #3b82f6;
}
</style>
