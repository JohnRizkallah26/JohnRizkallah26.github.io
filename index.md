---
layout: default
title: Home
---

# Welcome to My Site!

<!-- Live GMT Clock -->
<div id="gmt-clock"></div>

<!-- Rotating Quotes -->
<div id="quote-box"></div>

<!-- Visitor IP & Location -->
<div id="visitor-info"></div>

<nav class="dropdown-nav">
  <!-- Your existing dropdown sections remain unchanged -->
</nav>

---

<div class="image-gallery">
  <img src="IMG_6302.PNG" alt="Cyber Old Glory" />
</div>

<style>
/* GMT Clock styling */
#gmt-clock {
  position: fixed;
  top: 20px;
  left: 20px;
  background: #2c2c2c;
  color: #3b82f6;
  padding: 10px 15px;
  border-radius: 6px;
  font-family: "Segoe UI", Arial, sans-serif;
  font-size: 16px;
  font-weight: bold;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
  z-index: 9999;
}

/* Rotating Quotes styling */
#quote-box {
  position: fixed;
  bottom: 20px;
  left: 20px;
  max-width: 400px;
  background: #2c2c2c;
  color: #3b82f6;
  padding: 15px;
  border-radius: 6px;
  font-family: "Segoe UI", Arial, sans-serif;
  font-size: 15px;
  font-style: italic;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
  opacity: 0;
  transition: opacity 1.5s ease-in-out;
  z-index: 9999;
}

/* Visitor Info styling */
#visitor-info {
  position: fixed;
  top: 20px;
  right: 20px;
  max-width: 300px;
  background: #2c2c2c;
  color: #3b82f6;
  padding: 15px;
  border-radius: 6px;
  font-family: "Segoe UI", Arial, sans-serif;
  font-size: 14px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
  z-index: 9999;
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
const quotes = [
  "“All the great things are simple, and many can be expressed in a single word: freedom, justice, honor, duty, mercy, hope.” – Winston Churchill",
  "“The only thing we have to fear is fear itself.” – Franklin D. Roosevelt",
  "“Ask not what your country can do for you – ask what you can do for your country.” – John F. Kennedy"
];
let currentIndex = 0;
const quoteBox = document.getElementById("quote-box");

function updateQuote() {
  quoteBox.style.opacity = 0;
  setTimeout(() => {
    quoteBox.textContent = quotes[currentIndex];
    quoteBox.style.opacity = 1;
    currentIndex = (currentIndex + 1) % quotes.length;
  }, 1500);
}
updateQuote();
setInterval(updateQuote, 30000);

// Visitor IP & Location
async function fetchVisitorInfo() {
  try {
    const response = await fetch("https://ipapi.co/json/");
    const data = await response.json();
    document.getElementById("visitor-info").textContent =
      "Your IP: " + data.ip + " | Location: " + data.city + ", " + data.country_name;
  } catch (error) {
    document.getElementById("visitor-info").textContent = "Unable to fetch visitor info.";
  }
}
fetchVisitorInfo();
</script>
