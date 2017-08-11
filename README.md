# navbar
Navigation Bar Tabs
<doctype html>

<html>
	<head>
		<title>Professional Navigation Bar Tabs</title>
		<link rel="stylesheet" href="css/style.css" />
	<body>
		<div class="nav_bar">
		<ul>
			<li><a href="index.html" id="onlink">Home</a></li>
			<li><a href="about.html">About</a></li>
			<li><a href="gallery.html">Gallery</a></li>
			<li><a href="shop.html">Shop</a></li>
			<li><a href="feedback.html">Feedback</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
		</div>
		<div class="main_container">
			<p>This is the home page</p>
		</div>
	</body>	

</html>

<doctype html>

<html>
	<head>
		<title>Professional Navigation Bar Tabs</title>
		<link rel="stylesheet" href="css/style.css" />
	<body>
		<div class="nav_bar">
		<ul>
			<li><a href="index.html">Home</a></li>
			<li><a href="about.html" id="onlink">About</a></li>
			<li><a href="gallery.html">Gallery</a></li>
			<li><a href="shop.html">Shop</a></li>
			<li><a href="feedback.html">Feedback</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
		</div>
		<div class="main_container">
			<p>This is the about page</p>
		</div>
	</body>	

</html>

<doctype html>

<html>
	<head>
		<title>Professional Navigation Bar Tabs</title>
		<link rel="stylesheet" href="css/style.css" />
	<body>
		<div class="nav_bar">
		<ul>
			<li><a href="index.html">Home</a></li>
			<li><a href="about.html">About</a></li>
			<li><a href="gallery.html" id="onlink">Gallery</a></li>
			<li><a href="shop.html">Shop</a></li>
			<li><a href="feedback.html">Feedback</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
		</div>
		<div class="main_container">
			<p>This is the gallery page</p>
		</div>
	</body>	

</html>

<doctype html>

<html>
	<head>
		<title>Professional Navigation Bar Tabs</title>
		<link rel="stylesheet" href="css/style.css" />
	<body>
		<div class="nav_bar">
		<ul>
			<li><a href="index.html">Home</a></li>
			<li><a href="about.html">About</a></li>
			<li><a href="gallery.html">Gallery</a></li>
			<li><a href="shop.html"  id="onlink">Shop</a></li>
			<li><a href="feedback.html">Feedback</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
		</div>
		<div class="main_container">
			<p>This is the shop page</p>
		</div>
	</body>	

</html> 

<doctype html>

<html>
	<head>
		<title>Professional Navigation Bar Tabs</title>
		<link rel="stylesheet" href="css/style.css" />
	<body>
		<div class="nav_bar">
		<ul>
			<li><a href="index.html">Home</a></li>
			<li><a href="about.html">About</a></li>
			<li><a href="gallery.html">Gallery</a></li>
			<li><a href="shop.html"  id="onlink">Shop</a></li>
			<li><a href="feedback.html">Feedback</a></li>
			<li><a href="contact.html">Contact</a></li>
		</ul>
		</div>
		<div class="main_container">
			<p>This is the shop page</p>
		</div>
	</body>	

</html>

<doctype html>

<html>
	<head>
		<title>Professional Navigation Bar Tabs</title>
		<link rel="stylesheet" href="css/style.css" />
	<body>
		<div class="nav_bar">
		<ul>
			<li><a href="index.html">Home</a></li>
			<li><a href="about.html">About</a></li>
			<li><a href="gallery.html">Gallery</a></li>
			<li><a href="shop.html">Shop</a></li>
			<li><a href="feedback.html">Feedback</a></li>
			<li><a href="contact.html"  id="onlink">Contact</a></li>
		</ul>
		</div>
		<div class="main_container">
			<p>This is the contact page</p>
		</div>
	</body>	

</html>

body {
	margin: auto;
	background-color: green;
	font-family: arial;
}

.nav_bar {
	margin: auto;
	border-bottom: 1px solid #000000;
	width: 860px;
	padding: 0px 20px 0px 20px;
	height: 64px;
	margin-top: 30px;
}

.nav_bar ul {
	padding: 0;
	list-style: none;
}

.nav_bar ul li {
	float: left;
	font-weight: 16px;
	font-weight: bold;
	margin-right: 10px;
}

.nav_bar ul li a {
	text-decoration: none;
	color: #000000;
	background-color: #6db1e4;
	border: 1px solid #000000;
	border-bottom: none;
	padding: 23px 20px 22px 20px;
	-webkit-border-top-right-radius: 10px;
	-webkit-border-top-left-radius: 10px;
	width: 75px;
	display: block;
	text-align: center;
}

.nav_bar ul li a:hover {
	text-decoration: none;
	color: #000000;
	background-color: #96e0e9;
	-moz-transition: background-color 200ms ease-in;
	-webkit-transition: background-color 200ms ease-in;
	-ms-transition: background-color 200ms ease-in;
	-o-transition: background-color 200ms ease-in;
	transition: background-color 200ms ease-in;


}

.nav_bar ul li a#onlink {
	background-color: #ffffff;
	color: #000000;
	border-bottom: 1px solid #ffffff;
}

.nav_bar ul li a#onlink:hover {
	background-color: #ffffff;
	color: #000000;
}

.main_container {
	margin: auto;
	width: 860px;
	padding: 20px;
	border: 1px solid #000000;
	min-height: 400px;
	border-top: none;
	background: #ffffff;
}

.main_container p {
	font-size: 14px;
	margin: 0;
	padding: 0;
}