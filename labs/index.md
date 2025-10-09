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
</style>

<div id="content">
  <div id="side-nav">
    <ul id="nav-list">
      <li class="lab-selector">Lab 1 - Christiney</li>
      <li class="lab-selector">Lab 1 - Shawn</li>
      <li class="lab-selector">Lab 1 - Wes</li>
      <li class="lab-selector">Lab 1 - Yahya</li>
      <li class="lab-selector">Lab 1 - Zack Henderson</li>
      <li class="lab-selector">Lab 1 – Zach Boudreaux</li>
    </ul>
  </div>

  <div id="main">
    <!-- Lab 1 - Christiney -->
    <div class="lab-container">
      <div class="lab-title">
        <h2>Lab 1 – Christiney</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Christiney', '_blank')"></button>
      </div>
      <div>
        <iframe src="../resources/labs/Lab1-Christiney.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Shawn -->
    <div class="lab-container">
      <div class="lab-title">
        <h2>Lab 1 – Shawn</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Shawn', '_blank')"></button>
      </div>
      <div>
        <iframe src="../resources/labs/Lab1-Shawn.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Wes -->
    <div class="lab-container">
      <div class="lab-title">
        <h2>Lab 1 – Wes</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Wes', '_blank')"></button>
      </div>
      <div>
        <iframe src="../resources/labs/Lab1-Wes.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Yahya -->
    <div class="lab-container">
      <div class="lab-title">
        <h2>Lab 1 – Yahya</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-Yahya', '_blank')"></button>
      </div>
      <div>
        <iframe src="../resources/labs/Lab1-Yahya.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Zack Hendrickson -->
    <div class="lab-container">
      <div class="lab-title">
        <h2>Lab 1 – ZackHendrickson</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-ZackHendrickson', '_blank')"></button>
      </div>
      <div>
        <iframe src="../resources/labs/Lab1-ZackHendrickson.pdf" width="100%" height="600px"></iframe>
      </div>
    </div>

    <!-- Lab 1 - Zach Boudreaux -->
    <div class="lab-container">
      <div class="lab-title">
        <h2>Lab 1 – ZachBoudreaux</h2>
        <button class="btn" onclick="window.open('../resources/Lab1-ZachBoudreaux', '_blank')"></button>
      </div>
      <div>
        <iframe src="../resources/labs/Lab1-ZachBoudreaux.pdf" width="100%" height="600px"></iframe>
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
</script>
