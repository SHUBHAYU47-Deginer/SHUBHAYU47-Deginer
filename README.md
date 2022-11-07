<!DOCTYPE html>
<html>
<head>
	<title>project</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
	<style type="text/css">
    body {
    	     
            background-color: #BBBBBB;
			text-align: center;
		}

    ul.topnav {
      list-style-type: none;
      margin: 0;
      padding: 0;
      overflow: hidden;
      background-color: #333;
    }
    
    ul.topnav li {float: left;}
    
    ul.topnav li a {
      display: block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    
    ul.topnav li a:hover:not(.active) {background-color: #111;}
    
    ul.topnav li a.active {background-color: #04AA6D;}
    
    ul.topnav form.d-flex{float: right;}
    
    @media screen and (max-width: 600px) {
      ul.topnav li.right, 
      ul.topnav li {float: none;}
    }
    body{ 
			background-color: #EEEEEE;
			text-align: center;
		}
		#rcorners1 {
			margin-top: -2px;
  border-radius: 25px;
  background-image: linear-gradient(to bottom right, #FF0000,#FF0066,#FF00CC);
  padding: 20px; 
  width: 490px;
  height: 300px;
  margin: 0 20px;
  margin-right: 0 30px;
}

#rcorners2 {
  border-radius: 25px;
  background-image: linear-gradient(45deg,pink,skyblue,pink);
  padding: 20px; 
  width: 490px;
  height: 300px;
  margin: 0 20px;
  margin-right: 0 50px; 
}

#rcorners3 {
  border-radius: 25px;
  background-position: left top;
  background-repeat: repeat;
  padding: 20px; 
  width: 490px;
  height: 300px;
  background-image: linear-gradient(45deg,pink,skyblue,pink);
  margin: 0 20px;
  margin-right: 0 50px;
}
.box{
	display: flex;
	margin-left: 20px;
}
.dm{
  text-align: left;
}
.footer{
  display: flex;
  background: #00cccc;
  padding: 10px 300px;
  text-align: center;
  width: 100%;
  color: #ffF;
  font-weight: bolder;
}
.footer p{
  padding-left: 20px;
}
input[bl]{
	padding-bottom: 40px;
}
.dog{
  color: #333399;
  font-weight: bolder;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;  
}
.img-first{
 margin-right: 1190px;;
  margin-top: 10px;
}
.img-second{
  margin-left: 1190px;
}
.img-heading{
  height: 400px;
  margin-left: 50%;
  margin-top: -290px;
}
.img-six{
  height: 400px;
  margin-left: -1000px
}
.love{
  margin-top: -270px;
}
</style>

<body>

<ul class="topnav">
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#Course">Course</a></li>
  <li><a href="#Register">Register</a></li>
  <li><a href="#Login">Login</a></li>
  <li><a href="#Contact">Contact</a></li>
  <li class="right"><a href="#About">About</a></li>
  <form class="d-flex">
  		<input type="" list="bl" name="bl" placeholder="Language">
  	     <datalist id="bl">
  		<option>English</option>
  		<option>Bengali</option>
  		<option>Hindi</option>
  	   </datalist>
    <input class="form-control me-2" type="text" placeholder="Search">
    <button class="btn btn-primary" type="button">Search</button>
  </form>
  
</ul>

<div style="padding:0 16px;">
  
</div>
<img src="apply.jpeg" alt="" class="img-first">
<div class="dm">
	<h1>Easy to Learn<br> Easy to Know</h1>
</div>
<img src="apply4.jpg" alt="" class="img-heading"><br>
<img src="apply5.jpg" alt="" class="img-six">
<div class="love">
<div class="dm-about">
	<h1 style="margin-left: 1190px;">Grow up Skills in <br> Maxmium Budget</h1>
</div>
<img src="apply2.jpeg" alt="" class="img-second">
</div>
<br>
<div class="box">
<p id="rcorners1" style="font-weight:bolder; color:#ffF; font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;"><font size="18">let's learn something about Website & Web Design</font></p>
<p id="rcorners2" style="font-weight:bolder ;"><font size="10">Website</font><br>
 <font size="5"> What is Website ?</font><br>
  A Website is a collection of web pages  and related  Content that is identified by a common domain name and published on at least one web server . Example of notable websites Google , Facebook , Amazon and Wikipedia. All  publicly accessible websites collectively constitute the world  wide web.</p>
<p id="rcorners3" style="font-weight:bolder ;"><font size="10">Web Design</font><br>
  <font size="5"> What is Web Designing?</font>
<br>Web designing is the creation of websites and pages to reflect a company’s brand and information and ensure a user-friendly experience . Appearance and design are incorporated as vital elements whether you're designing a website , mobile app or maintaining content on a web page.
</p>
</div><br><br>
<div class="dog">
	<marquee>😊😎If you want oportunity to knock ,it's time to bulid a door.😎😀</marquee>
</div><br><br>
<footer>
  <div class="footer">
      <p>Facebook</p>
      <p>Twitter</p>
      <p>LinkedIn</p>
      <p>Discord</p>
      <p>Instagram</p>
      <p>© Copyright 2022</p>
      <p>© Copyright Shubhayu Bhattacharyya 2022</p>
  </div>
</footer>
</body>
</html>- 
