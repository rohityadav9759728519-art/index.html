<!DOCTYPE html> 

<html lang="en"> 

<head> 

<meta charset="UTF-8"> 

<title>Navigation Menu Example</title> 

<link rel="stylesheet" href="style-7.css"> 

</head> 

<body> 

&nbsp;

<header class="site-header"> 

&nbsp;  <h1>My Website</h1> 

</header> 

&nbsp;

<!-- Navigation Menu --> 

<nav class="nav-bar"> 

&nbsp;  <ul class="menu"> 

&nbsp;      <li class="menu-item"><a href="#">Home</a></li> 

&nbsp;      <li class="menu-item"><a href="#">About</a></li> 

&nbsp;      <li class="menu-item"><a href="#">Services</a></li> 

&nbsp;      <li class="menu-item"><a href="#">Contact</a></li> 

&nbsp;  </ul> 

</nav> 

&nbsp;

<section class="content-box"> 

&nbsp;  <h2>Welcome!</h2> 

&nbsp;  <p>This webpage demonstrates how different CSS display 

properties such as block, inline, inline-block, float, and clear 

affect the placement and alignment of navigation items. Each menu 

example shows the practical use of these properties in webpage 

layout design.</p> 

</section> 

&nbsp;

</body> 

</html>  

&nbsp;

\* { 

&nbsp;  margin: 0; 

&nbsp;  padding: 0; 

&nbsp;  box-sizing: border-box; 

&nbsp;  font-family: Arial; 

} 

&nbsp;

.site-header { 

&nbsp;  background: #222; 

&nbsp;  color: #fff; 

&nbsp;  padding: 15px; 

&nbsp;  text-align: center; 

} 

&nbsp;

.nav-bar { 

&nbsp;  background: #0066cc; 

&nbsp;  padding: 10px 0; 

} 

&nbsp;

.menu { 

&nbsp;  list-style: none; 

&nbsp;  text-align: center; 

} 

&nbsp;

.menu-item { 

&nbsp;  display: inline-block; 

&nbsp;  margin: 0 15px; 

} 

&nbsp;

.menu-item a { 

&nbsp;  text-decoration: none; 

&nbsp;  color: white; 

&nbsp;  font-size: 16px; 

} 

.content-box { 

width: 90%; 

background: #f2f2f2; 

margin: 20px auto; 

padding: 20px; 

border: 1px solid #ccc; 

} 

.content-box h2 { 

float: left; 

padding: 10px; 

} 

.content-box p { 

clear: both; 

margin-top: 10px; 

}

