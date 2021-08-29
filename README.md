
<!DOCTYPE html>
<html>
<style>
body {
    margin: 1px;
    font-family: 'Lato', sans-serif;
}

.overlay {
   height: 100%;
   width: 0;
   position: fixed;
   z-index: 1;
   top: 0;
   left: 0;
   background-color: red;
   background-color: green;
   overflow-x: hidden;
   transition: 0.5s;
}

.overlay-content {
    position: relative;
    top: 10%;
    width: 100%;
    text-align: right;
    margin-top: 20px;
    
}

.overlay a {
    padding: 8px;
    text-decoration: none;
    font-size: 36px;
    color: none;
    display: block;
    
}

.overlay a:hover, .overlay a:focus {
    color: #f1f1f1;
}

.overlay .closebtn {
    position: absolute;
    top: 20px;
    right: 45px;
    font-size: 60px;
}

/* When the height of the screen is less than
450 pixels, this will change the font-size of
the links and position the close button again,
so they don't overlap */ 

@media screen and (max-height:450px){
  .overlay a {font-size: 20px}
  .overlay .closebtn {
    font-size: 40px;
    top: 15px;
    right: 35px;
  }
}
#myInput {
  background-image:none;
  background-position: 10px 12px;
  background-repeat: no-repeat;
  box-sizing: border-box;
  width: 50%;
  font-size: 16px;
  padding: 5px 5px 5px 20px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
  border-radius: 50px;
  margin-left: 30px;
}
#Fb{
  float: left;
  width: 10%;
  font-size: 200%;
  color:white;
  margin: 0 0 0 0;
} 
.Dan{
  background-color: royalblue;
  padding: 20px;
  margin:0;

}
footer {
    background-color:steelblue;
    color:white;
    clear:both;
    text-align:center;
    padding:5px;   
    transition: 0.5s; 
}

.chip {
    display: inline-block;
    padding: 0 25px;
    height: 50px;
    font-size: 16px;
    line-height: 50px;
    border-radius: 25px;
    background-color: #f1f1f1;
    border: 10px;
    margin: 10px;
}

.chip img {
    float: left;
    margin: 0 10px 0 -25px;
    height: 50px;
    width: 50px;
    border-radius: 50%;
}

.search{
  text-align: center;
}

.chat{
  text-align:left;
}

.btn{
   background-color: red;
   color:white;
  
}

.fa{
  background-color: red;
  color: white;
}




</style>
<heade>

   <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
<body>
<header>
<section class="Dan">
<span style="font-size:30px;float:right;margin-bottom:1px;cursor:
pointer"

onclick="openNav()">&#9776;
</span>
<div id="myNav" class="overlay">
  <a href="javascript:void(0)" class=
  "closebtn"

  onclick="closeNav()">&times;</a>
  <div class="overlay-content">
    <a href="myaccount.html">My Account</a>
    <a href="login.html">LogIn</a>
    <a href="faq.html">FAQ</a>
    <a href="rules.html">T & Cs</a>
  </div>
</div>

<div class="chat"
<h2 id="Fb">DanLu</h2>
</div>



<div class="search">
<input type="text" id="myInput"
onkeyup="myFunction()" placeholder=
"Search by Name...."

title="Type in a name">

</div>




<buton><i style="font-size:24px;margin-right: 2px; padding: 0 0 0; color:none; float:right;" class="fa">&#xf0f3;</i></button>


<button style="padding: 2px 2px 0;float:left;margin-right: 2px;margin-bottom:5px;" class="btn"><i class="fa fa-home"></i></button>




<button style="margin:2px 100px 2px 100px;" class="btn"><i class="fa fa-archive"></i></button>

<script>
function openNav() {
 document.getElementById("myNav")
 .style.width = "100%";
}

function closeNav() {
 document.getElementById("myNav")
 .style.width = "0%";
}

</script>
</section>
<heade>

<div class="chip">
  <img src="images/danlucas.jpg" alt="Person"
  width="96" height="96">
  @danlucas.ke
</div>

<br>
<div class="chip">
  <img src="images/babajay.jpg" alt="Person"
  width="96" height="96">
  @Bj
</div>
<br>

<div class="chip">
  <img src="images/house1.jpg" alt="Person"
  width="96" height="96">
  @Jmy
</div>

<br>

<div class="chip">
  <img src="images/mumjay.jpg" alt="Person"
  width="96" height="96">
  @JLu
</div>
<br>

<div class="chip">
  <img src="images/family.jpg" alt="Person"
  width="96" height="96">
  @ken_one
</div>

<br>

<div class="chip">
  <img src="images/family2.jpg" alt="Person"
  width="96" height="96">
  @Cp
</div>

<br>

<div class="chip">
  <img src="images/mumjayshos.jpg" alt="Person"
  width="96" height="96">
  @Wsus
</div>

<br>
<div class=danlu>
For the codes of this website, please follow the link 👉
<a style="border:10px; margin: 10px; padding: 10px;"rel href="https://www.facebook.com/danlucas.ke/"> Follow for codes</a>

</div>

<footer>
Copyright  2021<br><a style="text-decoration: none;"><b style="color:black;">Email:</b><i style="color:red;">danlucas478@gmail.com</i></a>
<b style="color: blue;">||</b> 
<a style="text-decoration: none;color: red;" href="#"><b style="color:black;">Call:</b><i style="color:red;">+254790083726</i></a>

</footer>


</body>
</html>
