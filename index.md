<html>
<title>PRATEEK K V</title>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

 <meta charset="utf-8" /> 
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />

<style>
#loader { 
            border: 12px solid #f3f3f3; 
            border-radius: 50%; 
            border-top: 12px solid #444444; 
            width: 70px; 
            height: 70px; 
            animation: spin 1s linear infinite; 
        } 
          
        @keyframes spin { 
            100% { 
                transform: rotate(360deg); 
            } 
        } 
          
        .center { 
            position: absolute; 
            top: 0; 
            bottom: 0; 
            left: 0; 
            right: 0; 
            margin: auto; 
        }

<!-- side menu style start-->
body {
  font-family: "Lato", sans-serif;
}

.sidenav {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 1;
  top: -10px;
  left: 0px;
  background-color: black;
  overflow-x: hidden;
  transition: 0.5s;
  padding-top: 60px;
}

.sidenav a {
  padding: 8px 8px 8px 32px;
  text-decoration: none;
  font-size: 25px;
  color: red;
  display: block;
  transition: 0.3s;
}

.sidenav a:hover {
  color: blue;
}

.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
<!-- side menu style end-->

<!-- top menu style start-->
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;

}

.topnav {
  overflow: hidden;
  background-color: #333;
top: 50px;
position:fixed;
width:100%;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #4CAF50;
  color: white;
}
<!-- top menu style end-->

<!--glowing text style start-->
.glow {
  font-size: 80px;
  color: #fff;
  text-align: center;
  animation: glow 1s ease-in-out infinite alternate;
}

@-webkit-keyframes glow {
  from {
    text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #e60073, 0 0 40px #e60073, 0 0 50px #e60073, 0 0 60px #e60073, 0 0 70px #e60073;
  }
  
  to {
    text-shadow: 0 0 20px #fff, 0 0 30px #ff4da6, 0 0 40px #ff4da6, 0 0 50px #ff4da6, 0 0 60px #ff4da6, 0 0 70px #ff4da6, 0 0 80px #ff4da6;
  }
}
<!--glowing text style end-->

</style>

<style>
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: fixed;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  padding: 12px 16px;
  z-index: 1;
}

.dropdown:hover .dropdown-content {
  display: block;
  position:fixed;
  background-color:violet;
}
</style>

<style>
.divfnt {
font-size:25px;
}

#clsfnt{
background-color:lightgrey;
}
</style>

<style>
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 80;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
}

/* Modal Content */
.modal-content {
  background-color: #fefefe;
  margin: auto;
  padding: 20px;
  border: 1px solid #888;
  width: 80%;
}

/* The Close Button */
.close {
  color: #aaaaaa;
  float: right;
  font-size: 28px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
}
</style>

</head>

<body id="clsfnt">

<!-- page loader animation initialization start-->
<div id="loader" class="center"></div>
<!-- page loader animation initialization end-->


<!--side menu body start-->
<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
<a href="#" id="myBtn">About</a>

<!-- The Modal -->
<div id="myModal" class="modal">

  <!-- Modal content -->
  <div class="modal-content">
    <span class="close">&times;</span>
    <p4 style="font-size:30px;"> I am Prateek KV, a Final Year Student persuing B.Tech in Computer Science And Engineering at Presidency University, I had Completed my plus two from Narayana PU College. I am passionate to start my career and to give best out of me to the Company</p4>
  </div>

</div>
  <a href="https://prateekkv.github.io/prateek-academic/">Academics</a>
  <a href="https://sites.google.com/view/quickcoding/home" target="_blank">Other</a>
<div class="dropdown">
  <a href="#">contact</a>
  <div class="dropdown-content">
  <oi><a href="mailto:prateekkv14@gmail.com">Gmail</a>
  <a href="tel:+918867913376">Phone</a>
  </oi></div>
</div>

</div>

<span style="font-size:30px;position:fixed;cursor:pointer;" onclick="openNav()">&#9776; </span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
</script>
<!--side menu body end-->

<!--top menu body start-->
<div class="topnav">
  <a class="active" href="https://prateekkv.github.io/prateek/">Home</a>
  <a href="https://prateekkv.github.io/prateek-achievements/">Achievements</a>
  <a href="https://prateekkv.github.io/prateek-project/" target="_blank">Project</a>


<div class="dropdown">
  <a href="#contact">contact</a>
  <div class="dropdown-content">
  <oi><a href="mailto:prateekkv14@gmail.com">Gmail</a>
  <a href="tel:+918867913376">Phone</a>
  </oi></div>
</div>

</div>


<script>

var modal = document.getElementById("myModal");

// Get the button that opens the modal
var btn = document.getElementById("myBtn");

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks the button, open the modal 
btn.onclick = function() {
  modal.style.display = "block";
}

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  modal.style.display = "none";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>
<!--top menu body end-->

<pre>





</pre>
<p1><b><i><marquee style="font-size:20pt; height=35px; width=100%" scrollamount="12"  direction="left" behavior="" bgcolor="cyan"  onmouseover="this.stop()" onmouseout="this.start()">HELLO! WELCOME!!</marquee></i></b></p1>
<pre>

</pre>

<div class="divfnt">
<pre>Welcome and Thank You! for visiting. Hope you have good time browsing the site!

I am Prateek KV, Persuing B.Tech in Computer Science And Engineering(2017-2021) at
<a href="https://www.presidencyuniversity.in" target="_blank">Presidency University Bengaluru</a>.<br>
I have completed my 12th(2015-2017) in Stream(Physics,Chemistry,Mathematics,Computer Science, 
English And Sanskrit) at <a href="https://narayanajuniorcolleges.com/" target="_blank">Narayana PU College</a>.<br>
I have completed my 10th(2015) at <a href="https://www.adventistyearbook.org/entity?EntityID=30118" target="_blank">Seventh-Day Adventist</a>.



<center style="background-color:cyan;width:100%"> <a href="https://www.instagram.com/prateek14_" target="_blank"> <img src="https://drive.google.com/uc?export=view&id=1AQr6MYvJBhDhjA9tbIxtcNwlgJ0vS2iz" width="50" height="50"></a> <a href="https://www.facebook.com/profile.php?id=100005924508004" target="_blank"> <img src="https://drive.google.com/uc?export=view&id=11oxk6JGADHLUC9JNsEVlSH2aunwiui9_" width="50" height="50"></a> <a href="https://api.whatsapp.com/send?phone=918867913376" target="_blank"><img src="https://drive.google.com/uc?export=view&id=1YlvVrQbFFO9icXMJxU00NtnRx-F3OpMk" width="50" height="50"></a> <a href="mailto:prateekkv14@gmail.com" target="_blank"><img src="https://drive.google.com/uc?export=view&id=1yhpJ458DtEdrUCFnVGrYYepphElRitT_" width="50"height="50"></a> <a href="https://www.linkedin.com/in/prateek-kv-7352501b3" target="_blank"><img src="https://drive.google.com/uc?export=view&id=1PIDPQB3OLwSItHU5oCMQdapyT68cVk4H" width="50" height="50"></a></center>

</pre></div>


<!-- page loader ending start-->
<script> 
        document.onreadystatechange = function() { 
            if (document.readyState !== "complete") { 
                document.querySelector( 
                  "body").style.visibility = "hidden"; 
                document.querySelector( 
                  "#loader").style.visibility = "visible"; 
            } else { 
                document.querySelector( 
                  "#loader").style.display = "none"; 
                document.querySelector( 
                  "body").style.visibility = "visible"; 
            } 
        }; 
    </script>
<!-- page loader ending end-->

</body>
</html>
