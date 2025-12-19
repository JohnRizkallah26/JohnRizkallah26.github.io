---
layout: default
title: Home
---

# Welcome to My Site!

<!-- Cyber Sidebar -->
<div id="cyber-sidebar">
  <div id="gmt-clock"></div>
  <div id="visitor-info"></div>
  <div id="quote-box"></div>
</div>

<nav class="dropdown-nav">
  <details>
    <summary>👤 About</summary>
    <div class="dropdown-content">
      I am originally from Rochester, NY, and attended both Hilton and Brockport High Schools. Upon graduation in 2017, I enlisted in the US Navy as an Operations Specialist. I spent 3 years abroad in Rota, Spain. During this tour, I traveled to 12 countries and gained valuable experience in technology. In 2021, I transferred to Jacksonville, FL. During this tour, I was sent back overseas and provided support to CENTCOM. During this period, I also met my wife Lexi. In 2023, I transferred to NAS Key West where I serve as a Tactical Air Controller. I had my son, Eli, here and have made plenty of memories with my wife. I have spent much of this period focusing on cybersecurity education and certifications. I will be leaving the Navy in 2026 and will be working as a Cybersecurity Administrator. 
    </div>
  </details>

  <details>
    <summary>💻 Projects</summary>
    <div class="dropdown-content">
      <a href="https://github.com/JohnRizkallah26/home-network-recon-lab" target="_blank">Home Network Recon Lab</a><br>
      <a href="https://github.com/JohnRizkallah26/Windows-Group-Policy-Walkthrough" target="_blank">Windows Group Policy Walkthrough</a><br>
      <a href="https://github.com/JohnRizkallah26/Windows-Event-Viewer-Basics" target="_blank">Windows Event Viewer Basics</a><br>
      <a href="https://github.com/JohnRizkallah26/Basic-Ubuntu-Server-Hardening" target="_blank">Basic Ubuntu Server Hardening</a> 
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
/* Cyber Sidebar styling */
#cyber-sidebar {
  position: fixed;
  top: 20px;
  right: 20px;
  width: 280px;
  display: flex;
  flex-direction: column;
  gap: 15px;
  z-index: 1000;
}

/* GMT Clock */
#gmt-clock {
  background: #2c2c2c;
  color: #3b82f6;
  padding: 10px;
  border-radius: 6px;
  font-family: "Segoe UI", Arial, sans-serif;
  font-size: 14px;
  font-weight: bold;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
}



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
  color: #3b82f6;
}

/* Content styling */
.dropdown-content {
  margin-top: 8px;
  padding: 10px;
  background: #e6e6e6;
  color: #1d4ed8;
  border: 1px solid #888;
  border-radius: 6px;
  font-family: "Segoe UI", Arial, sans-serif;
  font-size: 15px;
  line-height: 1.6;
}

/* Style links inside dropdowns */
.dropdown-content a {
  color: #1d4ed8;
  text-decoration: none;
}

.dropdown-content a:hover {
  color: #0f172a;
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

<script>
// GMT Clock
function updateGMTClock() {
  const now = new Date();
  const gmtTime = now.toUTCString().split(" ")[4]; // HH:MM:SS
  document.getElementById("gmt-clock").textContent = "GMT Time: " + gmtTime;
}
setInterval(updateGMTClock, 1000);
updateGMTClock();

// Rotating Quotes


}
fetchVisitorInfo();
</script>
