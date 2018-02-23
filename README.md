# website
model website
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">

<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size:16px;}
.w3-half img{margin-bottom:-6px;margin-top:16px;opacity:0.8;cursor:pointer}
.w3-half img:hover{opacity:1}
</style>
<body>

<!-- Sidenav/menu -->
<nav class="w3-sidenav w3-blue w3-collapse w3-top w3-large w3-padding" style="z-index:3;width:300px;font-weight:bold" id="mySidenav"><br>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-padding-xlarge w3-hide-large w3-display-topleft w3-hover-white" style="width:100%;font-size:22px">Close Menu</a>
  <div class="w3-container">
    <h3 class="w3-padding-64"><b>WWFEC</b></h3>
  </div>
  <a href="#" onclick="w3_close()" class="w3-padding w3-hover-white">Home</a> 
  <a href="#services" onclick="w3_close()" class="w3-padding w3-hover-white">Services</a> 
  <a href="#reservations" onclick="w3_close()" class="w3-padding w3-hover-white">Reservations</a> 
  <a href="#contact" onclick="w3_close()" class="w3-padding w3-hover-white">Contact</a>
  <a href="#partypackages" onclick="w3_close()" class="w3-padding w3-hover-white">Party Packages</a>
  <a href="#availabilty" onclick="w3_close()" class="w3-padding w3-hover-white">Availability</a>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-blue w3-xlarge w3-padding">
  <a href="javascript:void(0)" class="w3-btn w3-blue w3-border w3-border-white w3-margin-right" onclick="w3_open()">☰</a>
  <span>The WWFEC</span>
</header>

<!-- Overlay efWWFECt when opening sidenav on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:340px;margin-right:40px">

  <!-- Header -->
  <div class="w3-container" style="margin-top:80px" id="showcase">
    <h1 class="w3-jumbo"><b>Water World Family Entertainment Center </b></h1>
  </div>
    
    
  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black w3-padding-0" onclick="this.style.display='none'">
    <span class="w3-closebtn w3-text-white w3-opacity w3-hover-opacity-off w3-xxlarge w3-container w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>

  <!-- Services -->
  <div class="w3-container" id="services" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-blue"><b>Services</b></h1>
    <hr style="width:50px;border:5px solid orange" class="w3-round">
    <p>The WWFEC is Family Entertainment Center that doubles as an amzing indoor and outdoor water park</p><br>

  <p> We offer an olympic pool with a full time lifegaurd, Monday through Friday 9am to 4pm. We have 12 different water slides, and an indoor kids waterpark, bumper cars, an arcade, laser tag, a full time gym and a state of the art spa.</p><br> 

    <p> We also have full time daycare for children ages 3-12 years.</p> <br>

<h3 class="w3-xxlarge w3-text-blue"><b>Snack bar</b></h3>
    <p>The snack bar will have a number of features such as smoothies, sandwiches, many different varieties of burgers and salads, soups and a slushie machine. The perfect thing to refresh you and your family after a swim at the WWFEC.</p>
   <p> The WWFEC offers a wonderful snack bar including many different dining options for the whole family.</p><br>



    <p> We offer lots of different classes and activities at the WWFEC for all ages, including, swim lessons, surf lesson, snorkeling lessons and water polo.</p><br>
    <p>The WWFEC also offers party rooms, to check availabilty and make reservations, check the availability option.</p><br>
     
  </div>


<!-- Snack Bar -->
  <div class="w3-container" id="reservations" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-blue"><b>Reservations</b></h1>
    <hr style="width:50px;border:5px solid orange" class="w3-round">
    <p> To Make Reservation at the WWFEC or plan your party package just put in you're contact information below and we wil get back to you with the details! </p>
  </div>

  <!-- Contact -->
  <div class="w3-container" id="contact" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-blue"><b>Contact</b></h1>
    <hr style="width:50px;border:5px solid orange" class="w3-round">
    <p>To contact us, or book a party package put you're contact information here and we'll get back to you as soon as possible!</p>
    <!-- www.123contactform.com script begins here -->
  


<script type="text/javascript" defer src="//www.123contactform.com/embed/2419376.js" data-role="form"></script>

<!-- Header -->
<div class="w3-container" id="partypackages" style="margin-top:75px">
  <h1 class="w3-xxxlarge w3-text-blue"><b>Party Packages</b></h1>
  <hr style="width:50px;border:5px solid orange" class="w3-round">

 </p>
    <br>
 <h3 class="w3-xlarge w3-text-black"><b>Under the Sea Party Package</b></h3>
    
    <p>The WWFEC also offers party packages including Under the Sea Party Package ($300), Our Under the Sea party Package includes hula skirts, party hats, cake and ice cream. </p><br>

<h3 class="w3-xlarge w3-text-black"><b>Beach Party Party Package</b></h3>

    Our Beach Party Party Package ($250), includes beach balls, a pineapple coconut fruit spread, Use of the pool and lifegaurd for 2 hours and shaved ice. To book you're party backage and check for availability please check the contact or availability option.</p><br>
   
  </div>


</div>
<!-- Header -->
<div class="w3-container" id="availabilty" style="margin-top:75px">
  <h1 class="w3-xxxlarge w3-text-blue"><b>Availability</b></h1>
  <hr style="width:50px;border:5px solid orange" class="w3-round">
  <header class="w3-display-container w3-content" style="max-width:1500px;">
    <img class="w3-image" src="images/overview2_Reduced.jpg" alt="The Hotel" style="min-width:1000px" width="1500" height="800">
    <div class="w3-display-right w3-padding w3-col l6 m8">
      <div class="w3-container w3-blue">
        <h4><i class="fa fa-bed w3-margin-right"></i>Water World Family Entertainment Center</h4>
        <script id="setmore_script" type="text/javascript" src="https://my.setmore.com/js/iframe/setmore_iframe.js"></script><a id="Setmore_button_iframe" style="float:none" href="https://my.setmore.com/bookingpage/e8edee49-3d9c-4ffc-93d7-58470e56cc1a"><img border="none" src="https://my.setmore.com/images/bookappt/SetMore-book-button.png" alt="Book an appointment with none using SetMore" /></a>
      </div>
    </div>
   </header>
</div>

<!-- Page content -->
<div class="w3-content" style="max-width:1532px;">

  <div class="w3-container w3-margin-top" id="rooms">
    <h2> Party Rooms</h2>
  </div>
  
  

  <div class="w3-row-padding w3-padding-16">
    <div class="w3-third w3-margin-bottom">
      <img src="images/jellyfish2_Reduced.jpg" alt="Norway" style="width:100%">
      <div class="w3-container w3-white">
        <h3>Jellyfish Room</h3>
        <h6 class="w3-opacity">From $99</h6>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <img src="images/shark2_Reduced.jpg" alt="Norway" style="width:100%">
      <div class="w3-container w3-white">
        <h3>Shark Room</h3>
        <h6 class="w3-opacity">From $149</h6>
        <script id="setmore_script" type="text/javascript" src="https://my.setmore.com/js/iframe/setmore_iframe.js"></script><a id="Setmore_button_iframe" style="float:none" href="https://my.setmore.com/bookingpage/e8edee49-3d9c-4ffc-93d7-58470e56cc1a"><img border="none" src="https://my.setmore.com/images/bookappt/SetMore-book-button.png" alt="Book an appointment with none using SetMore" /></a>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <img src="images/whale2_Reduced.jpg" alt="Norway" style="width:100%">
      <div class="w3-container w3-white">
        <h3>Whale Room</h3>
        <h6 class="w3-opacity">From $199</h6>
      </div>
    </div>
  </div>
  <!-- W3.CSS Container -->
<div >Powered by <a href="http://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-opacity">w3.css</a></p></div>

<p>Powered by <a class="footerLink13" title="123ContactForm" href="http://www.123contactform.com">123ContactForm</a> www.123contactform.com 

</body>
</html>
<!-- End page content -->
</div>

<script>
// Script to open and close sidenav
function w3_open() {
    document.getElementById("mySidenav").style.display = "block";
    document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
    document.getElementById("mySidenav").style.display = "none";
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


