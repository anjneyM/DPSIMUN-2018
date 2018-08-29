<!DOCTYPE html>
<html>
<title>DPSI MUN 2018</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<link rel="stylesheet" href="stylesheet.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>

<style>
.ai {
  background-color: #116466;
}
.button {
  display: inline-block;
  padding: 15px 25px;
  font-size: 24px;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  outline: none;
  color: #fff;
  background-color: #4CAF50;
  border: none;
  border-radius: 15px;
  box-shadow: 0 9px #999;
}

.button:hover {background-color: #3e8e41}

.button:active {
  background-color: #3e8e41;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}

body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
    height: 100%;
    color: #fff;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3, .bgimg-4 {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url(backRed.png);

    min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
    background-image: url("bg2.jpg");
    min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
    background-image: url("bg3.jpg");
    min-height: 400px;
}
.bgimg-4 {
    background-image: url("threat.jpg");
    min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

#about, #myNavbar, #contact{
  background-color: #2c3531;
}

#portfolio{
  background-color: #116466;
}
/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}

.cortana {
            position: relative;
            align-self: auto; }

a#lin:link, a#lin:visited {
    background-color: #2c3531;
    color: white;
    padding: 14px 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
}


a#lin:hover, a:active {
    background-color: #2c3531;
}
.sia {
  position:relative;
  left:350px;
}

.fade
{
        opacity:0.5;

}
.fade:hover
{
        opacity:1;
     -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}

.glow {
    color: white;
    text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px cyan;
}

.shade {
    color: lightgreen;
    text-shadow: -2px 0 black, 0 2px black, 2px 0 black, 0 -2px black;
    font-size:30px;
}

.glow {
    font-size:20px;
    text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px grey;
}
.glo{
        text-shadow: 0 0 3px #FF0000, 0 0 5px #0000FF;

}
.swing{
  position: relative;
          left:300px;
}
.swing:hover
{

        -webkit-animation: swing 1s ease;
        animation: swing 1s ease;
        -webkit-animation-iteration-count: 1;
        animation-iteration-count: 1;
}

@-webkit-keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(10px);
    }
    30%
    {
        -webkit-transform: translateX(-5px);
       transform: translateX(-10px);
    }
    50%
    {
        -webkit-transform: translateX(3px);
        transform: translateX(5px);
    }
    65%
    {
        -webkit-transform: translateX(-3px);
        transform: translateX(-5px);
    }
    80%
    {
        -webkit-transform: translateX(2px);
        transform: translateX(2px);
    }
    100%
    {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}
@keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(15px);
    }
    30%
    {
        -webkit-transform: translateX(-5px);
        transform: translateX(-15px);
    }
    50%
    {
        -webkit-transform: translateX(3px);
        transform: translateX(8px);
    }
    65%
    {
        -webkit-transform: translateX(-3px);
        transform: translateX(-8px);
    }
    80%
    {
        -webkit-transform: translateX(2px);
        transform: translateX(4px);
    }
    100%
    {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}
#Heading {
  padding-bottom: 10px;
  margin-bottom: 10px;
}
</style>
<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar" id="myNavbar">
    <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
      <i class="fa fa-bars"></i>
    </a>
    <a href="#home" class="w3-bar-item w3-button">HOME</a>
    <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> INFORMATION</a>
    <a href="#asp" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> ASPECTS</a>
       <a href="#threat" class="w3-bar-item w3-button w3-hide-small"> PROBLEMS</a>
    <a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>


    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right w3-hover-red">
      <i class="fa fa-search"></i>
    </a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
    <a href="#AI's" class="w3-bar-item w3-button" onclick="toggleFunction()">AI's</a>
    <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">PORTFOLIO</a>
    <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
    <a href="#" class="w3-bar-item w3-button">SEARCH</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home" >
  <div class="w3-display-middle" style="white-space:nowrap;">
    <center> <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity"> <span class="w3-hide-small">
      <div style="background-color:#5903ff; font-size: 20px; opacity:0.75;"><img src="MUNLogo.png"width="250" height="250" class="cortana" ><p align="center" id="Heading"> <h1>DPSIMUN</h1> </p> </div>
    </span> </center>

  </div>
</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <img src="MUNLogo.png"width="250" height="250" class="cortana" >


          <video width="320" height="240" class="sia" autoplay loop muted >
  <source src="jet.mp4" type="video/mp4">

  Your browser does not support the video tag.
</video>


  <h3 class="w3-center glow"> <b> ABOUT ARTIFICIAL INTELLIGENCE (A.I.)</b> </h3>
  <p class="w3-center"><em>Artificial Intelligence is about replacing human decision making with more sophisticated  technologies - Falgun Desai</em></p>
  <p>
 <b>Artificial Intelligence (AI) </b> is usually defined as the science of making computers do things that require intelligence when done by humans. AI has had some success in limited, or simplified, domains. However, the five decades since the inception of AI have brought only very slow progress, and early optimism concerning the attainment of human-level intelligence has given way to an appreciation of the profound difficulty of the problem. <br>
 The first classifies AI systems as either <i> 'Weak AI' </i> or <i> 'Strong AI' </i>. <br> Weak AI, also known as Narrow AI, is an AI system that is designed and trained for a particular task. Virtual personal assistants, such as Apple's Siri, are a form of weak AI.
<br>
Strong AI, also known as artificial general intelligence, is an AI system with generalized human cognitive abilities so that when presented with an unfamiliar task, it has enough intelligence to find a solution.   <i>The Turing Test</i>, developed by mathematician Alan Turing in 1950, is a method used to determine if a computer can actually think like a human, although the method is controversial.
  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <img src="ss.jpg" class="swing" alt="Photo of Me" width="400" height="500" >
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-padding-large">
      <p>
    </div>
  </div>
  <p class="w3-large w3-center w3-padding-16">INTELLENGENCE IS THE ABILITY TO ADAPT TO CHANGE<br> Will Artificial Intellegence be a threat to humanity? </p>
  <p class="w3-wide"><i class="fa fa-food"></i>NO</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:37%">37%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-plastics"></i>NOT SURE</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:16%">16%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-paper"></i>YES</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:48%">48%</div>
  </div>
</div>

<div class="w3-row w3-center w3-dark-grey w3-padding-16">
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">57</span><br>
    Major Artificial Intellgence Companies
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">$19.34 BILLION</span><br>
    INVESTMENT
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">109+</span><br>
	Countries Available
	</div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">NONE</span><br>
  Threats Faced
  </div>
</div>

<div id="asp"><!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide">ASPECTS</span>

  </div>
</div>

<!-- Container (Portfolio Section) -->
<div class="w3-content w3-container w3-padding-64" id="portfolio">
    <img src="MUNLogo.png"width="250" height="250" class="cortana" >

            <video width="320" height="240" class="sia" autoplay loop muted >
  <source src="jet.mp4" type="video/mp4">
  >
  Your browser does not support the video tag.
</video>

  <h3 class="w3-center shade">Here is a broader understanding of Artificial Intellegence</h3>
  <p class="w3-center gloww"><em>Here are some experiments using Artificial Intellegence<br> Click on a thumbnail to make view description</em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="MUNLogo.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Pie Chart">
    </div>

    <div class="w3-col m3">
      <img src="MUNLogo.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Coffee beans">
    </div>

    <div class="w3-col m3">
      <img src="MUNLogo.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Bear closeup">
    </div>

    <div class="w3-col m3">
      <img src="MUNLogo.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Quiet ocean">
    </div>
  </div>

  <div class="w3-row-padding w3-center w3-section">
    <div class="w3-col m3">
      <img src="five.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="The mist">
    </div>

    <div class="w3-col m3">
      <img src="six.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="My beloved typewriter">
    </div>

    <div class="w3-col m3">
      <img src="seven.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Empty ghost train">
    </div>

    <div class="w3-col m3">
      <img src="eight.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Sailing">
    </div>

  </div>
</div>




<div id="threat"><!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-4 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide"> THREAT? </span>

  </div>
</div>

<!-- Info bla bla -->
<div class="w3-content w3-container w3-padding-64" style="background-color: #CCCCCC;" >
    <img src="MUNLogo.png"width="250" height="200" class="cortana" >
    <video width="320" height="240" class="sia" autoplay loop muted >
  <source src="jet.mp4" type="video/mp4">
  >
  Your browser does not support the video tag.
</video>
  <h3 class="w3-center glo"> ARTIFICIAL INTELLIGENCE- <span style="color:white; font-size: 37px ; "> <b> <i> Goon </i> </b> </span>
    or <span style="color:white; font-size: 35px ; "> <b> <i> Boon? </i> </b> </span> </h3>
  <p class="w3-center"><em style="font-size:20px;">The question isn't whether will it work. The question is, if it does, how important will it be?</em></p>
  <p>
 <font style="font-family:Comic Sans Ms; font-size:17px;"> <p> This year, arguably the world's greatest living scientific mind, Stephen Hawking, and its leading techno-industrialist, Elon Musk, voiced their fears about the potentially lethal rise of artificial intelligence. They were joined by philosophers, physicists and computer scientists, all of whom spoke out about the serious risks posed by the development of greater-than-human machine intelligence. </p>
 <p> In a widely cited op-ed co-written with MIT physicist Max Tegmark, Nobel laureate Frank Wilczek and computer scientist Stuart Russell, Hawking sounded the AI alarm. "One can imagine (AI) outsmarting financial markets, out-inventing human researchers, out-manipulating human leaders, and developing weapons we cannot even understand. Whereas the short-term impact of AI depends on who controls it, the long-term impact depends on whether it can be controlled at all." </p> <font style="font-family:Comic Sans Ms;">

  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <p><b><i class="fa fa-user w3-margin-right"></i> WHY  MAY ARTIFICIAL INTELLEGENCE BE A THREAT </b></p><br>
      <img src="Elon.jpg" style="border-radius: 25px;" class="w3-round w3-image w3-opacity w3-hover-opacity-off fade" alt="Photo of Me" width="500" height="333">
            <img src="Hawk.jpg" style="position:relative; left:500px; top:-200px; border-radius: 25px;"   class="w3-round w3-image w3-opacity w3-hover-opacity-off fade" alt="Photo of Me" width="500" height="333">
</div>
    </div>


<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>


</div>
<!-- Third Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">CONTACT</span>
  </div>
</div>

<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="contact">
  <h3 class="w3-center">We're here for a change</h3>
  <p class="w3-center"><em>And we'd love your feedback!</em></p>

  <div class="w3-row w3-padding-32 w3-section">
    <div class="w3-col m4 w3-container">
      <!-- Add Google Maps -->
      <div id="googleMap" class="w3-round-large w3-greyscale" style="width:100%;height:400px;"></div>
    </div>
    <div class="w3-col m8 w3-panel">
      <div class="w3-large w3-margin-bottom">
        <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Delhi Public School Indirapuram<br>
        <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Phone: +91 9999999999<br>
        <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Email: make_a_change@gmail.com<br>
      </div>
      <p>Swing by for a cup of <i class="fa fa-coffee"></i>, or leave me a note:</p>
      <form action="/action_page.php" target="_blank">
        <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
          </div>
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
          </div>
        </div>
        <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
        <button class="w3-button w3-black w3-right w3-section" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </form>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
</footer>

<!-- Add Google Maps -->
<script>
function myMap()
{
  myCenter=new google.maps.LatLng(28.6479, 77.3763);
  var mapOptions= {
    center:myCenter,
    zoom:12, scrollwheel: false, draggable: false,
    mapTypeId:google.maps.MapTypeId.ROADMAP
  };
  var map=new google.maps.Map(document.getElementById("googleMap"),mapOptions);

  var marker = new google.maps.Marker({
    position: myCenter,
  });
  marker.setMap(map);
}

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
        navbar.className = "w3-bar" + " w3-card-2" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card-2 w3-animate-top w3-white", "");
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
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCwFieoEoo-027k6DU0pi8DsH8C7w5yCsA&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->

</body>
</html>
