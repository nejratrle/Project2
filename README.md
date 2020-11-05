# Project2
<!DOCTYPE html>
<html>
<head>
	<!-- Name: Nejra Trle
		 Course: CS412
		 Assignment: Project 2-HTML (Resume)
		 Due Date: November 5, 2020
		 Purpose: gain a better understanding of basic CSS-->
	<title>My CV</title>
	<meta charset="UTF-8"/>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
<main>
<header>
<h1>Nejra Trle </h1>
<pre>
Address: Branislava Nušića 100, Sarajevo, Bosnia and Herzegovina 
D&POB: 29/08/1998, Sarajevo 
email: <a href="mailto:nejra_trle@hotmail.com">nejra_trle@hotmail.com</a>
Phone: +38761072851
</pre>
</header>
<br></br><hr>
<article>
<section class="experience">
<h3>Experience</h3> 
<br>
<dl>
  <dt>  <a href="https://teach.engoo.com/app/teach?biboLegacy=true";>Bibo Global Opportunity, Inc // 06/2017 to date </a>  </dt>
  </br>
  <dd>Online English Tutor </dd>
  <br></br>
  <dt>Market Pik 5 d.o.o. Sarajevo // 06/2016 -> 08/2016 </dt>
  <!-- no link here because the store does not exist anymore-->
  </br>
  <dd>Store Clerk</dd>
</dl>
</section>
<section class="education">
<h3>Education</h3> 
<br>
<dl>
   <dt> <a href="https://www.ius.edu.ba">International University of Sarajevo // 09/2017 to date </a></dt>
  <br>
  <dd>  First Cycle of Computer Science and Engineering Studies</dd>
  <br></br>
  <dt> <a href="http://bosnjackagim.edu.ba">First Bosniak High School Sarajevo // 09/2013 -> 06/2017</a></dt>
  </br>
  <dd> Cambridge International School</dd>
  <br></br></br>
  <dt> <a href="http://osas.edu.ba"> O.Š. “Aleksa Šantić” // 09/2004 -> 06/2013</a> </dt>
  <br>
</dl>
</section>
</article>
</main>
<aside>
<br>
<img src="https://scontent.xx.fbcdn.net/v/t1.15752-0/p280x280/122271709_954869655004362_2880440767277404139_n.jpg?_nc_cat=110&ccb=2&_nc_sid=ae9488&_nc_ohc=y4f8f4q9ppsAX8OGTa0&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&tp=6&oh=4c1cb97653c3712948646d6a85301db6&oe=5FB62E34"; alt="My picture"; class="center" />

<br><div class="aboutme"><hr>
<h2> About me </h2> 

<p>
I am a computer science student looking for experience in the field. I am communicative, ready for the challenges that come with responsibility and quickly process new knowledge and skills. </br>
Team work is not a problem for me, as I have been in the position of the team leader quite often.</br>
My goal is to gain work experience in order to upgrade existing knowledge and try myself in a professional environment. In the future, I plan to enroll in the second cycle of studies in the field of Management.</br>
</p> 
<div class="skill"><hr>
<h3> Skills </h3> 

<ul>
  <li>MS Office</li>
  </br>
  <li>Java</li>
  </br>
  <li>C++</li>
  </br>
  <li>English Language</li>
  </br>
  <li>Driver's license, Category B</li>
  </br>
</ul>
</div>
</aside>
<br></br><hr>
<footer>
<h4>See my last project&nbsp; <a href="https://nejratrle.github.io/p1mycv/";>here</a></h4>
</footer>
</body>
</html>
h1{
	color:#610000; 
	text-align:center;
	font-weight: bold;
	font-size: 100px;
}
h2{
	color:#610000;
	font-style: italic;
}
h3{
	color:#610000;
	font-weight: bold;
}
h4{
	color:#610000;
	font-weight: bold;
}
pre{
	text-align:center;
}
a{
	color:black;
}
body{
	background-color:#DBD2D0; 
}
p{
	font-style: italic;
	text-align: justify;
	
}
dt{
	font-weight: bold;
}
dt{
	color:grey;
	font-style: italic;
}
.skills{
	text-align:center;
}
li{
	font-style: italic;
}
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 2px;
  margin-top: 2px;
}
header{
	background-color:#DBD2D0;
	margin-top: 0;
    margin-right: 4em;
    margin-bottom: 0;
    margin-left: 4em;
}
aside{
	position: fixed;
	right: 0;
	top: 39px;
	width: 20%;
	height: 100%;
	box-sizing: border-box;
	padding: 0px 20px;
	background-color:#947575; 	
	border-left: 1px #002395;
}
.experience{
    width:40%;
    float:left;
   
    padding:0;  
	margin-right: 4em;
    margin-bottom: 0.5em;
    margin-left: 4em;
}
.education{
  width:40%;
    float:left;
    margin-right: 4em;
    margin-bottom: 0.5em;
    margin-left: 4em;
}
footer{
  clear: both;
  position: fixed;
  left: 0;
  bottom: 10%;
  width: 100%;
  text-align: center;
}
