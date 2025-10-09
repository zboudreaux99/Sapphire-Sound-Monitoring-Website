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
      <li class="lab-selector" id="lab1-christiney">Lab 1 - Christiney</li>
      <li class="lab-selector" id="lab1-shawn">Lab 1 - Shawn</li>
      <li class="lab-selector" id="lab1-wes">Lab 1 - Wes</li>
      <li class="lab-selector" id="lab1-yahya">Lab 1 - Yahya</li>
      <li class="lab-selector" id="lab1-zack">Lab 1 - Zack Hendrickson</li>
      <li class="lab-selector" id="lab1-zach">Lab 1 – Zach Boudreaux</li>
    </ul>
  </div>

  <div id="main">
    <!-- Lab 1 - Christiney -->
    <div class="lab-container" id="lab1-christiney-container">
      <div class="lab-title">
        <h2>Lab 1 – Christiney</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Christiney.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Christiney.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Shawn -->
    <div class="lab-container" id="lab1-shawn-container">
      <div class="lab-title">
        <h2>Lab 1 – Shawn</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Shawn.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Shawn.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Wes -->
    <div class="lab-container" id="lab1-wes-container">
      <div class="lab-title">
        <h2>Lab 1 – Wes</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Wes.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Wes.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Yahya -->
    <div class="lab-container" id="lab1-yahya-container">
      <div class="lab-title">
        <h2>Lab 1 – Yahya</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Yahya.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-Yahya.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Zack Hendrickson -->
    <div class="lab-container" id="lab1-zack-container">
      <div class="lab-title">
        <h2>Lab 1 – Zack Hendrickson</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-ZackHendrickson.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-ZackHendrickson.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Zach Boudreaux -->
    <div class="lab-container" id="lab1-zach-container">
      <div class="lab-title">
        <h2>Lab 1 – Zach Boudreaux</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-ZachBoudreaux.pdf', '_blank')"> Open in new tab </button>
      </div>
      <div>
        <iframe src="../resources/Lab1-ZachBoudreaux.pdf" width="100%" height="100%"></iframe>
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
  showLab('lab1-christiney');
</script>
<!-- <script>
  function hideLabs() {
    const labs = document.getElementsByClassName("lab-container");
    for (let lab of labs) {
      lab.style.display = 'none';
    }
  }

  function showLab(labName) {
    const divId = labName + "-div";
    const lab = document.getElementById(divId);
    if (lab) lab.style.display = 'block';
  }

  document.addEventListener('click', function(event) {
    if (event.target.classList.contains('lab-selector')) {
      hideLabs();
      showLab(event.target.id);
    }
  });

  // Default view
  hideLabs();
  showLab('lab1');
</script> -->
