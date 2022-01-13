# resume
<!DOCTYPE html>
<html lang="en">
<title>WELCOME TO NURALISHA WEBSITES</title>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size:16px;}
.w3-half img{margin-bottom:-6px;margin-top:16px;opacity:0.8;cursor:pointer}
.w3-half img:hover{opacity:1}
</style>
<body>

	<script src="https://cdn.bootcss.com/jquery/3.2.1/jquery.js"></script>
    <script>
        function snow() {
            //1, define a snowflake template
            var flake = $("<div>").css({
                "position": "absolute",
                "color": "#fff"
            }).html("❄️");
 
            //Get the width of the page, use this number to calculate, the value of left when the snowflake starts
            var documentWidth = $(document).width();
 
            //Get the height of the page, which is equivalent to the position of the Y axis when the snowflakes fall
            var documentHieght = $(document).height();
 
            //Define the number of milliseconds to generate a snowflake
            var millisec = 100;
            //2, set the first timer, a periodic timer, and generate a snowflake every time (millisec);
            setInterval(function() {
                //Randomly generate the value of left at the beginning of the snowflake falling, which is equivalent to the position of the X axis at the beginning
                var startLeft = Math.random() * documentWidth;
 
                //Randomly generate the value of left at the end of snowflake falling, which is equivalent to the position of the X axis at the end
                var endLeft = Math.random() * documentWidth;
 
                // Randomly generate snowflake size
                var flakeSize = 5 + 20 * Math.random();
 
                //Randomly generate the falling duration of snowflakes
                var durationTime = 4000 + 7000 * Math.random();
 
                //Randomly generate the transparency at the beginning of falling snowflakes
                var startOpacity = 0.7 + 0.3 * Math.random();
 
                //Randomly generate the transparency at the end of falling snowflakes
                var endOpacity = 0.2 + 0.2 * Math.random();
 
                //3. Clone a snowflake template, define the initial style of the snowflake, and stitch it into the page
                flake.clone().appendTo($("body")).css({
                    "left": startLeft,
                    "opacity": startOpacity,
                    "font-size": flakeSize,
                    "top": "-25px",
                }).animate({ //Execute animation
                    "left": endLeft,
                    "opacity": endOpacity,
                    "top": documentHieght
                }, durationTime, function() {
                    //4. When the snowflake falls, delete the snowflake.
                    $(this).remove(); 
                });
            }, millisec);
        };
        snow();
    </script>
 

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-black w3-collapse w3-top w3-large w3-padding" style="z-index:3;width:300px;font-weight:bold;" id="mySidebar"><br>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-hide-large w3-display-topleft" style="width:100%;font-size:22px">Close Menu</a>
  <div class="w3-container">
    <p align="center"><img src="images/lish.jpg" width="170" height="200">
    <h3 class="w3-padding-64"><b>NURALISHA<br>NASIR</b></h3>
  </div>
  <div class="w3-bar-block">
    <a href="lish.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Home</a> 
    <a href="Objectives.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Objectives</a> 
    <a href="Skills.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Skills</a> 
    <a href="Achievements.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Achievements</a>  
    <a href="Curricular.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Curricular</a>
    <a href="Education.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Education</a> 
    <a href="Experiences.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Experiences</a> 
    <a href="References.html" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">References</a>
  </div>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-black w3-xlarge w3-padding">
  <a href="javascript:void(0)" class="w3-button w3- black w3-margin-right" onclick="w3_open()">☰</a>
  <span>NURALISHA NASIR</span>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:340px;margin-right:40px">

  <!-- Header -->
  <audio controls autoplay>
  <source src="music/bgsound.mp3">
</audio>
  <div class="w3-container" style="margin-top:80px" id="showcase">
<font color="rebeccapurple"> <marquee direction="left"> <h1 class="w3-jumbo"><b>::Welcome to My Resume Website::</b></h1></marquee></font>

     
 <font color="darkcyan" ><p><h4>NURALISHA BINTI NASIR</h4></p> 

<p><h5>E-mail : alishanasir24@gmail.com
<br> Phone : +60 1140798810
<br> Address: No. 41B, Quarters Tnb, Jalan Baru, 13600, Perai, Pulau Pinang.</h5></p></font>
</div>
  

  <!-- Services -->
  <div class="w3-container" id="services" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text rosybrown"><font color="palevioletred"><b>Personal Summary</b></font></h1>
    <hr style="width:50px;border:5px solid plum" class="w3-round">
  <font color="purple"><p> I am a self-motivated, diligent individual. History and management fascinate me tremendously. I will also be able to quickly pick up new skills and expertise.</p>

<br> I enjoy exploring the internet for information on current events, such as pandemics, natural disasters, and other topics. All of the information helps me increase my general knowledge and allows me to spend some time alone.</font>
  </div>

<div class="w3-container" id="services" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-burly wood"><font color="palevioletred"><b>Family and Me</b></font></h1>
    <hr style="width:50px;border:5px solid plum" class="w3-round">
     <p align="left"><img src="images/family.jpg" width="300" height="230"> 
      <font color="purple"><p> MY FAMILY</p>
      <br> I have 6 family members and all my siblings are girls. My older sister is married and has one child. Both my younger sisters are still study at USM and KPTM. My father work as a technician while my mother is a housewife. I am the second child in the family and study at UiTM Machang Kelantan.</font>
</div>


<!-- W3.CSS Container -->
<div class="w3-light-grey w3-container w3-padding-32" style="margin-top:75px;padding-right:58px"><p class="w3-right">Developed by Nuralisha Nasir © 2022 </a></p></div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}
</script>

</body>
</html>
