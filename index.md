---
layout: default
title: Home
---

# Welcome to My Site

## 👤 About
Hey everyone! I am originally from Rochester, NY & graduated from Brockport High School. I enlisted in the Navy in 2017 as an Operations Specialist. I spent 3 years abroad in Rota, Spain. This experience heavily shaped me as it forced me out of my comfort zone. I made hundreds of friends and gained valuble experience with computer systems. However, I also made hundreds of mistakes, which I am also extremely grateful for as it has molded me into a better human. I have lived in Florida since 2021, and will be leaving the Navy in 2026.

---

<button class="accordion">💻 Projects</button>
<div class="panel">
  Showcase your GitHub repositories, portfolio, or case studies.
</div>

<button class="accordion">✍️ Education/Credentials</button>
<div class="panel">
  Security + (Expires in 2028)<br>
  B.S in Cybersecurity<br>
  Google Cybersecurity Certificate<br>
  Secret Clearance
</div>

<button class="accordion">📬 Contact Info</button>
<div class="panel">
  Email: johnrizkallah3@gmail.com
</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
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
});
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
  padding: 10px;
  display: none; /* hidden by default */
  background-color: #f9f9f9;
  border-radius: 6px;
  margin-bottom: 8px;
}
</style>

