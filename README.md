# bubble.github.io
<!DOCTYPE html>
<html>
<link rel="stylesheet" href="w3bsite.css">
<link rel="stylesheet" href="webbb.css">
<link rel="stylesheet" href="webbb.js">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Arial;
    font-size: 17px;
}

.container {
    position: relative;
    max-width: auto;
    margin: 0 auto;

}

.container img {
  vertical-align:middle;
 }

.container .content {
    position: absolute;
    bottom: 0;
    background: rgba(0, 0, 0, 0.5); /* Black background with transparency */
    color: #f1f1f1;
    width: 100%;


    }
img {
  /*  -webkit-filter: blur(2px); /* Safari 6.0 - 9.0 */
  /*  filter: blur(2px); */
  }
h1 {
   text-shadow: 3px 2px black;
    font-size: 80px;
    color: white;
}


.navbar {
    overflow: hidden;
    background-color:rgba(0,0,0,.65);
    font-family: Arial, Helvetica, sans-serif;
}

.navbar a {
    float: left;
    font-size: 16px;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

.dropdown {
    float: left;
    overflow: hidden;
}

.dropdown .dropbtn {
    font-size: 16px;
    border: none;
    outline: none;
    color: white;
    padding: 14px 16px;
    background-color: inherit;
    font-family: inherit;
    margin: 0;
}

.navbar a:hover, .dropdown:hover .dropbtn {
    background-color: grey;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    float: none;
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {
    background-color: #ddd;
}

.dropdown:hover .dropdown-content {
    display: block;
}



#myBtn {
    display: none; /* Hidden by default */
    position: fixed; /* Fixed/sticky position */
    bottom: 20px; /* Place the button at the bottom of the page */
    right: 30px; /* Place the button 30px from the right */
    z-index: 99; /* Make sure it does not overlap */
    border: none; /* Remove borders */
    outline: none; /* Remove outline */
    background-color: Black; /* Set a background color */
    color: white; /* Text color */
    cursor: pointer; /* Add a mouse pointer on hover */
    padding: 15px; /* Some padding */
    border-radius: 10px; /* Rounded corners */
    font-size: 18px; /* Increase font size */
}

#myBtn:hover {
    background-color: #555; /* Add a dark-grey background on hover */
}


body {
    background-color: #FFFFFF;
}

.header {
  background-color: #f1f1f1;
  padding: 30px;
  text-align: center;


</style>
</head>
<body>



<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>


<div class="navbar">
  <a href="#home">Home</a>
  <a href="#aboutus">About Us</a>
  <a href="#currentcrises">Current Crises</a>
  <a href="#preservetheworld">Preservation of the World</a>
  <a href="#getinvolved">Get Involved</a>
  <img class="logo-img" src="logo.png">
</div>



<div id="overlay">
    <video class="visible-desktop" id="hero-vid" autoplay loop muted>
        <source type="video/mp4" src="winter.mp4"></source>
    </video>

    <img id="hero-pic" class="hidden-desktop" src="winter.mp4" alt="">
</div>



<script>
// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
    if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
        document.getElementById("myBtn").style.display = "block";
    } else {
        document.getElementById("myBtn").style.display = "none";
    }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
    document.body.scrollTop = 0; // For Safari
    document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
}




</script>



<div id="home">
  <div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <center><img class="big-logo" src="logo.png"><center>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
  </div>
</div>



<div id="aboutus">
   <div id="content">
     <img class="red" src="about.png">
     <div class="myMyMyMyWords">ABOUT US:</div>
     <div class="words">
     <div class="wordsNow">
     <br>
     <br>
     With a deep interest in technology, the four of us (Eva Heinrich, Genia Kapelonis, Hazel Nolasco, Lena Choe) gathered in the Warner Brothers Technology building for the Girls Who Code SIP. All of us, originally having no knowledge of computer science, walked in nervously and oblivious of what was to come. After many weeks of preparation, we figured that it was our duty to give back to the community through this website. Our website's mission is to inspire teens to actively use their voice   to help out not only their community, but the ones around the world.</div>
   </div>
   </div>
</div>

<style>

h1 {
  font-size:30px;
}

mark {

    background-color: #363433;
    color: whiteSmoke;

}
</style>



<div id="currentcrises">

<div id="Current Crisis">
  <div class="bgimg-4">
    <div class="par1">
    <br>
    <br>
    <p><div class="myCenter"><mark>Current Crises</mark></div></p>
   </div>
  </div>

<div id="content">
  <img class="blue" src="immigration.jpg">
  <center><div class="nowImm">Immigration</div><center>
  <center><input type = "button" class = "btn" onClick ="location.href= 'immigration.html';"value = "Read More" ></center>
</div>
</div>



<div id="content">
  <img class="blue" src="hunger.jpg">
  <center><div class="nowHunger">Hunger and Poverty in America</div><center>
  <center><input type = "button" class = "btn" onClick ="location.href= 'hunger.html';"value = "Read More" ></center>
</div>
</div>


<div id="content">
  <img class="blue" src="im3.jpg">
  <center><div class="nowMass">Mass Shootings</div><center>
  <center><input type = "button" class = "btn" onClick ="location.href= 'mass_shootings.html';"value = "Read More" ></center>
</div>
</div>

<div id="content">
  <img class="blue" src="homelessness.jpg">
  <center><div class="nowHom">Homelessness</div><center>
  <center><input type = "button" class = "btn" onClick ="location.href= 'homelessness.html';"value = "Read More" ></center>
</div>
</div>
</div>

<div id="preservetheworld">
  <div class="bgimg-1">
    <div class="par1">
    <br>
    <br>
    <p><div class="myCenter"><mark>Preservation of the World</mark></div></p>
   </div>
  </div>

  <div id="content">
    <img class="img-container" src="https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fblogs-images.forbes.com%2Ftrevornace%2Ffiles%2F2015%2F11%2Fbeautiful-places-world-1200x900.jpg">
    <div class="myMyMyWords">Preserve the Beauty:</div>
    <div class="myMyWords">
    <div class="meWords">Despite all the crises going on in the world there are many beautiful places. However they will cease to prosper if we do not take action now. To see some ways of how you can help the world visit the "Get Involved" page.
  </div>
  </div>
  </div>
</div>


<div id="getinvolved">
  <div class="bgimg-2">
    <div class="par2">
    <br>
    <br>
    <p><div class="myCenter"><mark>GETTING INVOLVED</mark></div></p>
   </div>
  </div>

  <div id="content">
    <img class="red" src="https://ncscolour.com/wp-content/uploads/2016/04/tempcolorimg-558.jpg">
    <div class="myMy">
    <div class="wordsNowNow">Explore the links below to see how you can get involved today:</div>
    <h1> <a href = 'http://www.standupforkids.org/'
    target="_blank "> 1) http://www.standupforkids.org/</a></h1>
    <h1> <a href= 'https://www.salvationarmyusa.org/usn/'
    target ='_blank'> 2) https://www.salvationarmyusa.org/usn/</a> </h1>
    <h1> <a href = 'http://www.thp.org/'
    target="_blank"> 3) http://www.thp.org/</a> </h1>
    <h1> <a href = 'https://www.raicestexas.org/'
    target ='_blank'> 4) https://www.raicestexas.org/</a> </h1>
    <h1> <a href = 'https://marchforourlives.com/'
    target ="_blank"> 5) https://marchforourlives.com/</a></h1>
    <h1> <a href ='https://www.nilc.org/'
    target ='_blank'> 6) https://www.nilc.org/</a></h1>


  </div>
  </div>
</div>


</body>
</html>
