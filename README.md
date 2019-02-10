<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src = "/script.js"></script>
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="/style.css">
<body style="background-color:#F9FFFF;">
<style>
  div.background-image {
  width: 100%;
  height: 640px;
  background-image: url("https://i.pinimg.com/originals/78/c5/a3/78c5a31fad9f93c0789ce551d6cd6c95.jpg");
  background-repeat: no-repeat;
  background-position: center top
  }
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
  height: 100%;
  color: #277;
  line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
  round-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
  background-image: url('/w3images/parallax1.jpg');
  min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
  background-image: url("/w3images/parallax2.jpg");
  min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
  background-image: url("/w3images/parallax3.jpg");
  min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1600px) {
  .bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: scroll;
    min-height: 400px;
  }
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar" id="myNavbar">
    <a class="w3-bar-item w3-button w3-hover-light-greyw3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
      <i class="fa fa-bars"></i>
    </a>
    <a href="#home" class="w3-bar-item w3-button">HOME</a>
    <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> 
      <i class="fa fa-search"></i>
    </a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
    <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-button" w3-button">SEARCH</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home" class="center">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity">AdDRESS the<span class="w3-hide-small"> </span> Weather</span>
  </div>
</div>
<div class="background-image"></div>
</div>
<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT THIS WEBSITE</h3>
  <p class="w3-center"><em> </em></p>
  <p> Hello! We will predict your #OOTD based on the weather - all you have to do is input your location and voila, you have a perfect outfit! </p>

  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <p><b><i class="fa fa-user w3-margin-right"></i>Please type in your city here:</b></p><br>
<body>
  <!-- <div class="topnav"> -->

<p id="weatherReport"> </p>
Location: <input type="text" id="zipCode" value=" Enter in location . . ."><br>
<button onclick="myFunction()">Enter</button>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-padding-large">
      <p></p>
    </div>

  <div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">Types of Outfits</h3>
  <p class="w3-center"><em> </em></p>
  <p>  </p>
    <div>
    <ul class="Types of Outfits">
      <h3="Types of Outfits"></h3><br>
   <li><button onclick="onClickAthletic()" class="w3-button w3-padding-large w3-light-blue w3-center" style="margin-top:64px">ATHLETIC</button></li><br>
    <div id="x"></div>
   <li> <button onclick="onClickCute()" class="w3-button w3-padding-large w3-pink"  style="margin-top:64px">CUTE</button> </li> <br>
   <div id="y"></div>
   <li><button onclick="onClickFormal()" class="w3-button w3-padding-large w3-black" style="margin-top:64px">FORMAL</button></li><br> 
   <div id="a"></div> 
  <li><button onclick="onClickCasual()" class="w3-button w3-padding-large w3-light-green" style="margin-top:64px">CASUAL</button></li>
 <div id="b"></div> 
  </div>


<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Third Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">CONTACT</span>
  </div>
</div>


 
<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
    }
}

// Used to toggle the menu on small screens when clicking on the menu button
function toggleFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else {
        x.className = x.className.replace(" w3-show", "");
    }
}

//weather location
function myFunction() {
  var innerText = document.getElementById("zipCode").value;
  console.log(innerText)
  console.log("text")
  if (innerText == "Philadelphia") {
document.getElementById("weatherReport").innerText = "Right now it's 29 degrees but feels like 23 degrees. Click on your style to get an outfit inspo for this weather";
  }
}

//outfits
function onClickAthletic() {
var img = document.createElement("img");
 
img.src = "https://i.imgur.com/TkwiCTJ.png";
var src = document.getElementById("x");
 
src.appendChild(img);
}
function onClickCute() {
var img = document.createElement("img");
 
img.src = "https://i.imgur.com/z6iyYh4.png";
var src = document.getElementById("y");
 
src.appendChild(img);
}
function onClickFormal() {
var img = document.createElement("img");
 
img.src = "https://i.imgur.com/FtsjKfT.png";
var src = document.getElementById("a");
 
src.appendChild(img);
}
function onClickCasual() {
var img = document.createElement("img");
 
img.src = "https://i.imgur.com/1DAx7gt.png";
var src = document.getElementById("b");
 
src.appendChild(img);
}

</script>

</body>
</html>
