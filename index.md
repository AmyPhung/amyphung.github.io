---
layout: page
title: Hello World! I'm Amy.
subtitle: Olin Student / Robotics Nerd / Engineer
bigimg: /img/walle2.jpg
---

## Here are some of my favorite projects:



.container {
    display: grid;
    grid-gap: 5px;
    grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
    grid-template-rows: repeat(2, 100px);
}
.container > div > img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

<div class="container">
  <div><img src="img/tractor.jpg"/></div>
  <div><img src="img/tractor.jpg"/></div>
  <div><img src="img/tractor.jpg"/></div>
  <div><img src="img/tractor.jpg"/></div>
  <div><img src="img/tractor.jpg"/></div>
  <div><img src="img/tractor.jpg"/></div>
</div>














<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
    box-sizing: border-box;
}

.column {
    float: left;
    width: 33.33%;
    padding: 10px;
}

.row:after {
    content: "";
    display: table;
    clear: both;
}
</style>
</head>
<body>

<div class="row">
  <div class="column">
    <a href="https://amyphung.github.io/gravl/">
      <img src="img/tractor.jpg" style="width:100%">
    </a>
    <h3>Autonomous Tractor Research</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit...</p>
    <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris...</p>
  </div>
  <div class="column">
    <a href="https://amyphung.github.io/roc/">
      <img src="img/roc.jpg" style="width:100%">
    </a>
    <h3>Rotorcraft Operations Center</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit...</p>
    <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris...</p>
  </div>
  <div class="column">
    <a href="https://amyphung.github.io/fruit-ninja/">
      <img src="img/fruit-ninja.jpg" style="width:100%">
    </a>
    <h3>OpenCV Fruit Ninja</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit...</p>
    <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris...</p>
  </div>
</div>

</body>
