---
layout: default
title: Home
---

# Welcome to My Site!

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
    <a href="https://github.com/JohnRizkallah26/home-network-recon-lab" target="_blank">
      Home Network Recon Lab
    </a>
  </div>
</details>

  <details>
    <summary>✍️ Education/Credentials</summary>
    <div class="dropdown-content">
      Comptia Security + (Expires in 2028)<br>
      B.S in Cybersecurity<br>
      Google Cybersecurity Certificate<br>
      Secret Clearance
    </div>
  </details>

 <details>
  <summary>📚 Helpful Publications</summary>
  <div class="dropdown-content">
    <a href="https://www.nist.gov" target="_blank">Visit NIST Website</a><br>
    <a href="https://www.nist.gov/cyberframework" target="_blank">NIST Cybersecurity Framework (CSF)</a><br>
    <a href="https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final" target="_blank">NIST SP 800-53 Security Controls</a><br>
    <a href="https://csrc.nist.gov/publications/detail/sp/800-171/rev-2/final" target="_blank">NIST SP 800-171 (CUI Protection)</a><br>
    <a href="https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final" target="_blank">NIST SP 800-61 Incident Response Guide</a><br>
    <a href="https://csrc.nist.gov/projects/risk-management" target="_blank">NIST Risk Management Framework (RMF)</a>
  </div>
</details>
</nav>

---

<div class="image-gallery">
  <img src="IMG_6302.PNG" alt="Cyber Old Glory" />
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

/* Style links inside dropdowns */
.dropdown-content a {
  color: #3b82f6;        /* Blue text */
  text-decoration: none; /* Remove underline */
  font-weight: bold;
}

.dropdown-content a:hover {
  color: #3b82fb;        
  text-decoration: underline;
}

/* Image gallery styling */
.image-gallery {
  display: flex;
  justify-content: center;
  margin-top: 30px;
}

.image-gallery img {
  max-width: 600px;
  width: 100%;
  height: auto;
  border-radius: 12px;
  border: 3px solid #3b82f6;
}
</style>
