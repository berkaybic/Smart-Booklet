# Smart-Booklet
<!doctype html>
<!-- Website template by freewebsitetemplates.com -->
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Contact - SmartBooklet </title>
	<link rel="stylesheet" href="css/style.css" type="text/css">
	<link rel="stylesheet" type="text/css" href="css/mobile.css">
	<script src="js/mobile.js" type="text/javascript"></script>
</head>
<body>
	<div id="page">
		<div id="header">
			<div id="navigation">
				<span id="mobile-navigation">&nbsp;</span>
				<a href="index.html" class="logo"><img src="images/logo1.png"width="208" height="107" alt=""></a>
				<ul id="menu">
					<li>
						<a href="index.html">Home</a>
					</li>
					<li>
						<a href="about.html">About</a>
					</li>
					
					
					<li class="selected">
						<a href="contact.html">Contact</a>
					</li>
				</ul>
			</div>
		</div>
		<div id="body" class="contact">
			<div>
				<h1>Contact us</h1>
				<img src="images/map.png" alt="">
				<h2>ADDRESS</h2>
				<div class="col-sm-4">
				<center><iframe src="https://www.google.com/maps/d/embed?mid=14pdrcOGxmjOm12G2UdZkG2-hDaULLFEp" width="600" height="400"></iframe></center>
				</div>
				<h2>Email</h2>
				<a href="index.html">info@smartbooklet.com</a>
				<h4>Ask a Question</h4>
				<form action="index.html">
					<input type="text" name="name" value="Name" onblur="this.value=!this.value?'Name':this.value;" onfocus="this.select()" onclick="this.value='';">
					
					<input type="text" name="Email" value="Email" onblur="this.value=!this.value?'Email':this.value;" onfocus="this.select()" onclick="this.value='';">
					<textarea name="meassage" cols="50" rows="7">Message</textarea>
					<input type="submit" value="Send" id="submit">
				</form>
			</div>
		</div>
		<div id="footer">
			<div>
				<div class="connect">
					<a href="" class="twitter">twitter</a>
					<a href="" class="facebook">facebook</a>
				</div>
				<p>&copy; 2019 by SmartBooklet. All rights reserved.</p>
			</div>
		</div>
	</div>
</body>
</html>
