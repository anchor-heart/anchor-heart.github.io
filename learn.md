<html lang="en">
<head>
<link href="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<title>Anchorheart</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="author" content="Taybah Mohammad">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/js/bootstrap.bundle.min.js"></script>
<!--fonts-->
<script src="https://kit.fontawesome.com/ad53426853.js" crossorigin="anonymous"></script>
<style>

* {
  box-sizing: border-box;
}

/* Float four columns side by side */
.column {
  float: left;
  width: 25%;
  padding: 0 10px;
}

/* Remove extra left and right margins, due to padding */
.row {margin: 0 -5px;}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive columns */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}

/* Style the counter cards */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  background-color: #f1f1f1;
}

 body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  display: block;
  color: ##f1f1f1;
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
  background-color: #04AA6D;
  color: white;
}

.topnav .icon {
  display: none;
}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}


/*style the list in the footer*/
nav2 {
  text-align: center;
  width: 500%;
  height: 200px; /* only for demonstration, should be removed */
  background: ;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 100%;
  background-color: #f1f1f1;
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}


.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}

.center {
  text-align: center;
}

</style>
</head>
<body>

<div class="topnav" id="myTopnav">
  <a href="https://anchor-heart.github.io/index.html" class="active">Home</a>
  <a href="#Learn">Learn</a>
  <a href="https://anchor-heart.github.io/message.html">Contact</a>
  <a href="https://anchor-heart.github.io/owner.html">Owner</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>

<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>

<header>
 <h1 class="center" style="font-size:50px;">Learn</h1>
</header>

<div class="row">
  <div class="column">
    <div class="card">
      <h3>Seeking a Professional</h3>
      <p>Some text</p>
      <p><button class="button" onclick="window.location.href='https://anchor-heart.github.io/learn_pages/professional.html';">More</button></p>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <h3>Becoming a Therapist</h3>
      <p>Some text</p>
      <p><button class="button" onclick="window.location.href='https://anchor-heart.github.io/learn_pages/therapist.html';">More</button></p>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <h3>Stress</h3>
      <p>Some text</p>
      <p><button class="button" onclick="window.location.href='https://anchor-heart.github.io/learn_pages/stress.html';">More</button></p>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <h3>Insomnia</h3>
      <p>Some text</p>
      <p><button class="button" onclick="window.location.href='https://anchor-heart.github.io/learn_pages/insomnia.html';">More</button></p>
    </div>
  </div>
</div>

<br>

<div class="row">
  <div class="column">
    <div class="card">
      <h3>Anxiety</h3>
      <p>Some text</p>
      <p><button class="button" onclick="window.location.href='https://anchor-heart.github.io/learn_pages/anxiety.html';">More</button></p>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <h3>Depression</h3>
      <p>Some text</p>
      <p><button class="button" onclick="window.location.href='https://anchor-heart.github.io/learn_pages/depression.html';">More</button></p>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <h3>Suicide</h3>
      <p>Some text</p>
      <p><button class="button" onclick="window.location.href='https://anchor-heart.github.io/learn_pages/suicide.html';">More</button></p>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <h3>Eating Disorders</h3>
      <p>Some text</p>
      <p><button class="button" onclick="window.location.href='https://anchor-heart.github.io/learn_pages/eating-disorder.html';">More</button></p>
    </div>
  </div>
</div>

<div class="footer-clean">
    <footer>
        <div class="container">
            <div class="row justify-content-center">
                    <div class="col-sm-4 col-md-3 item">
                        <h3>About</h3>
                        <ul>
                            <li><a href="https://anchor-heart.github.io/owner.html">Owner</a></li>
                            <li><a href="#">What We Do</a></li>
                            <li><a href="https://anchor-heart.github.io/FAQS.html">FAQS</a></li>
                        </ul>
                    </div>
                    <div class="col-sm-4 col-md-3 item">
                        <h3>Join Us</h3>
                        <ul>
                            <li><a href="https://anchor-heart.github.io/volunteer.html">Volunteer</a></li>
                            <li><a href="https://anchor-heart.github.io/client.html">Client</a></li>
                        </ul>
                    </div>
                    <div class="col-sm-4 col-md-3 item">
                        <h3>Other</h3>
                        <ul>
                            <li><a href="https://anchor-heart.github.io/terms.html">Terms & Conditions</a></li>
                            <li><a href="https://anchor-heart.github.io/message.html">Questions & Feedback</a></li>
                            <li><a href="#">Privacy Policy</a></li>
                        </ul>
                    </div>
                    <div class="col-lg-3 item social"><a href="#"><i class="icon ion-social-facebook"></i></a><a href="#"><i class="icon ion-social-twitter"></i></a><a href="#"><i class="icon ion-social-snapchat"></i></a><a href="#"><i class="icon ion-social-instagram"></i></a>
                        <p class="copyright">Anchorheart © 2022</p>
                    </div>
                </div>
            </div>
        </footer>
    </div>
    

<!-- Credit to https://epicbootstrap.com/snippets/footer-with-columns -->
