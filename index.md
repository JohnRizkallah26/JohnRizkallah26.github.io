---
layout: default
title: Home
---

# Welcome to My Site

<nav style="display:flex; gap:20px; background:#f5f5f5; padding:10px; border-radius:6px;">
  <a href="#home" style="text-decoration:none; font-weight:bold;">Home</a>
  <a href="#about" style="text-decoration:none; font-weight:bold;">About</a>
  <a href="#projects" style="text-decoration:none; font-weight:bold;">Projects</a>
  <a href="#education" style="text-decoration:none; font-weight:bold;">Education</a>
  <a href="#contact" style="text-decoration:none; font-weight:bold;">Contact</a>
</nav>

---

## 👤 About
Hey everyone! I am originally from Rochester, NY & graduated from Brockport High School. I enlisted in the Navy in 2017 as an Operations Specialist. I spent 3 years abroad in Rota, Spain. This experience heavily shaped me as it forced me out of my comfort zone. I made hundreds of friends and gained valuble experience with computer systems. However, I also made hundreds of mistakes, which I am also extremely grateful for as it has molded me into a better human. I have lived in Florida since 2021, and will be leaving the Navy in 2026.

---

<button class="accordion">💻 Projects</button>
<div class="panel">
  <p>Showcase your GitHub repositories, portfolio, or case studies.</p>
</div>

<button class="accordion">✍️ Education/Credentials</button>
<div class="panel">
  <p>Security + (Expires in 2028)<br>
  B.S in Cybersecurity<br>
  Google Cybersecurity Certificate<br>
  Secret Clearance</p>
</div>

<button class="accordion">📬 Contact Info</button>
<div class="panel">
  <p>Email: johnrizkallah3@gmail.com</p>
</div>

---

<script>
  // Simple accordion toggle
  const acc = document.getElementsByClassName("accordion");
  for (let i = 0; i < acc.length; i++) {
    acc[i].addEventListener("click", function() {
      this.classList.toggle("active");
      const panel = this.nextElementSibling;
      if (panel.style.display === "block") {
        panel.style.display = "none";
      } else {
        panel.style.display = "block";
      }
    });
  }
</script>

<style>
  .accordion {
    background-color: #eee;
    color: #333;
    cursor: pointer;
    padding: 12px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 16px;
    font-weight: bold;
    margin-top: 8px;
    border-radius: 6px;
  }

  .accordion:hover {
    background-color: #ddd;
  }

  .panel {
    padding: 0 12px;
    display: none;
    background-color: #f9f9f9;
    border-radius: 6px;
    margin-bottom: 8px;
  }
</style>


