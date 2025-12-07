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
      However, I also made hundreds of mistakes, thanks to some amazing leaders and collegues, I have been able to learn from them. 
      I have lived in Florida since 2021, and will be leaving the Navy in 2026 en route to San Antonio, Texas. At home I have my Wife of 4 years (Lexi) and my son Eli. 
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
    <summary>📬 Contact Info</summary>
    <div class="dropdown-content">
      Email: johnrizkallah3@gmail.com
    </div>
  </details>
</nav>

<style>
/* Navigation container */
.dropdown-nav {
  display: flex;
  flex-direction: column;
  gap: 10px;
  background: #2c2c2c; /* darker gray to blend with Midnight theme */
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
  background: #444; /* darker button background */
  color: #1e3a8a;   /* dark blue text */
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
  color: #0f172a; /* even darker navy on hover */
}

/* Content styling */
.dropdown-content {
  margin-top: 8px;
  padding: 10px;
  background: #e6e6e6; /* slightly darker than pure white */
  color: #1e3a8a;      /* dark blue text for readability */
  border: 1px solid #888;
  border-radius: 6px;
}
</style>
