---
title: Labs
---
# Labs
<style>
  #content {
    display: flex;
  }
  #side-nav {
    width: 20%;
  }
  #main {
    width: 80%;
  }
  #nav-list {
    list-style: none;
    padding-left: 0;
  }
  .lab-selector:hover {
    color: #2b6f6d;
    cursor: pointer;
  }
  .lab-title h2 {
    margin-bottom: 0.5em;
  }
  iframe {
    border: 1px solid #ccc;
    border-radius: 8px;
  }
  .btn {
    background-color: #2b6f6d;
    color: white;
    border: none;
    border-radius: 6px;
    padding: 8px 12px;
    cursor: pointer;
  }
  .btn:hover {
    background-color: #74b49b;
  }
  .lab-selector {
    padding: 8px;
    margin: 4px 0;
    border-radius: 4px;
    transition: all 0.2s;
  }
  .lab-selector.active {
    background-color: #2b6f6d;
    color: white;
  }
  .lab-container {
    display: none;
  }
</style>

<div id="content">
  <div id="side-nav">
    <ul id="nav-list">
      <h3>Lab 1</h3>
      <li class="lab-selector" id="lab1-christiney">Christiney</li>
      <li class="lab-selector" id="lab1-shawn">Shawn</li>
      <li class="lab-selector" id="lab1-wes">Wes</li>
      <li class="lab-selector" id="lab1-yahya">Yahya</li>
      <li class="lab-selector" id="lab1-zack">Zack Hendrickson</li>
      <li class="lab-selector" id="lab1-zach">Zach Boudreaux</li>
      <li class="lab-selector" id="lab1-brian">Brian</li>
      <li class="lab-selector" id="lab1-alisa">Alisa</li>
      <li class="lab-selector" id="lab1-priscilla">Priscilla</li>
      <li class="lab-selector" id="lab1-outline">Lab 1 Outline</li>
      <h3>Lab 2</h3>
      <li class="lab-selector" id="lab2-christiney">Christiney</li>
      <li class="lab-selector" id="lab2-shawn">Shawn</li>
      <li class="lab-selector" id="lab2-wes">Wes</li>
      <li class="lab-selector" id="lab2-yahya">Yahya</li>
      <li class="lab-selector" id="lab2-zack">Zack Hendrickson</li>
      <li class="lab-selector" id="lab2-zach">Zach Boudreaux</li>
      <li class="lab-selector" id="lab2-brian">Brian</li>
      <li class="lab-selector" id="lab2-alisa">Alisa</li>
      <li class="lab-selector" id="lab2-priscilla">Priscilla</li>
      <li class="lab-selector" id="lab2-section3">Lab 2 Section 3</li>
    </ul>
  </div>

  <div id="main">
    <div class="lab-container" id="lab1-outline">
      <div class="lab-title">
        <h2>Lab 1 Outline</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Outline.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Outline.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-section3-container">
      <div class="lab-title">
        <h2>Lab 2 Section 3</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-Section3.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-Section3.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Christiney -->
    <div class="lab-container" id="lab1-christiney-container">
      <div class="lab-title">
        <h2>Lab 1 – Christiney</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Christiney.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Christiney.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-christiney-container">
      <div class="lab-title">
        <h2>Lab 2 – Christiney</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-Christiney.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-Christiney.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Shawn -->
    <div class="lab-container" id="lab1-shawn-container">
      <div class="lab-title">
        <h2>Lab 1 – Shawn</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Shawn.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Shawn.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-shawn-container">
      <div class="lab-title">
        <h2>Lab 2 – Shawn</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-Shawn.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-Shawn.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Wes -->
    <div class="lab-container" id="lab1-wes-container">
      <div class="lab-title">
        <h2>Lab 1 – Wes</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Wes.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Wes.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-wes-container">
      <div class="lab-title">
        <h2>Lab 2 – Wes</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-Wes.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-Wes.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Yahya -->
    <div class="lab-container" id="lab1-yahya-container">
      <div class="lab-title">
        <h2>Lab 1 – Yahya</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Yahya.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Yahya.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-yahya-container">
      <div class="lab-title">
        <h2>Lab 2 – Yahya</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-Yahya.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-Yahya.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Zack Hendrickson -->
    <div class="lab-container" id="lab1-zack-container">
      <div class="lab-title">
        <h2>Lab 1 – Zack Hendrickson</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-ZackHendrickson.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-ZackHendrickson.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-zack-container">
      <div class="lab-title">
        <h2>Lab 2 – Zack Hendrickson</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-ZackHendrickson.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-ZackHendrickson.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Zach Boudreaux -->
    <div class="lab-container" id="lab1-zach-container">
      <div class="lab-title">
        <h2>Lab 1 – Zach Boudreaux</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-ZachBoudreaux.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-ZachBoudreaux.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-zach-container">
      <div class="lab-title">
        <h2>Lab 2 – Zach Boudreaux</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-ZachBoudreaux.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-ZachBoudreaux.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Brian -->
    <div class="lab-container" id="lab1-brian-container">
      <div class="lab-title">
        <h2>Lab 1 – Brian</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Brian.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Brian.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-brian-container">
      <div class="lab-title">
        <h2>Lab 2 – Brian</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-Brian.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-Brian.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Alisa -->
    <div class="lab-container" id="lab1-alisa-container">
      <div class="lab-title">
        <h2>Lab 1 – Alisa</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Alisa.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Alisa.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-alisa-container">
      <div class="lab-title">
        <h2>Lab 2 – Alisa</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-Alisa.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-Alisa.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Priscilla -->
    <div class="lab-container" id="lab1-priscilla-container">
      <div class="lab-title">
        <h2>Lab 1 – Priscilla</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Priscilla.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Priscilla.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>

    <div class="lab-container" id="lab2-priscilla-container">
      <div class="lab-title">
        <h2>Lab 2 – Priscilla</h2>
        <button class="btn" onclick="window.open('../resources/Lab2-Priscilla.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab2-Priscilla.pdf" width="100%" height="1000px"></iframe>
      </div>
    </div>
  </div>
</div>

<script>
  function hideLabs() {
    const labs = document.getElementsByClassName("lab-container");
    for (let lab of labs) {
      lab.style.display = 'none';
    }
    const navItems = document.getElementsByClassName("lab-selector");
    for (let item of navItems) {
      item.classList.remove('active');
    }
  }

  function showLab(labName) {
    const containerId = labName + "-container";
    const lab = document.getElementById(containerId);
    if (lab) {
      lab.style.display = 'block';
      const navItem = document.getElementById(labName);
      if (navItem) navItem.classList.add('active');
    }
  }

  document.addEventListener('click', function(event) {
    if (event.target.classList.contains('lab-selector')) {
      hideLabs();
      showLab(event.target.id);
    }
  });

  hideLabs();
  showLab('lab2-section3');
</script>
