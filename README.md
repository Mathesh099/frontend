<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Anime Waver</title>
	<style type="text/css">
		html{
			font-family: "Lato", "helvetica neue", "helvetica" "Arial", sans-serif;
		}
		body{
			background-color: #ffffff;
			margin: 0;
		}
		p{
			color: #5d6660;
			font-size: 16px;
			line-height: 24px;
			font-family: "Lato", "helvetica neue", "helvetica" "Arial", sans-serif;
		}
		header{
			height: 80px;
			background-color: #ffffff;
		}
		#header-container{
			width: 85%;
			margin: auto;
		}
		.col-3{
			width: 33%;
			float: left;
		}
		.logo{
			padding-top: 15px;
		}
		.menu{
			margin-top: 40px;
		}
		.menu li{
			list-style-type: none;
			display: inline;
			font-size: .80em;
			color: #8e8e8e;
			padding-right: 30px;
		}
		.getStartedBTN{
			background-color: #6dc77a;
			border-radius: 25px;
			-moz-border-radius: 25px;
			-webkit-border-radius: 25px;
			text-decoration: none;
			color: #ffffff;
			padding: 10px 26px;
			margin-top: 30px;
			display: inline-block;
			font-size: 17px;
			float: right;
		}
		#top-section-main{
			background-image: url("new sec1.jpg");
			height: 740px;
			border: none;
		}
		#top-section-content{
			width: 60%;
			margin-left: auto;
			margin-right: auto;
			margin-top: 0;
		}
		#top-section-content h1{
			font-size: 3.5em;
			font-weight: 300;
			color: #ffffff;
			text-align: center;
			margin-top: 0;
			margin-bottom: 15px;
			padding-top: 90px;
		}
		#top-section-content p{
			font-size: 1.3em;
			font-weight: 400;
			color: #ffffff;
			text-align: center;
			margin-top: 0;

		}
		.play-button{
			margin-left: auto;
			margin-right: auto;
			display: block;
			padding: 40px 0 100px 0;
		}
		.main-form h6{
			font-family: sans-serif;
			font-size: .9em;
			font-weight: 100;
			color: #ffffff;
			text-align: center;
		}
		.main-form input{
			margin: 0;
			width: 30%;
			height: 40px;
			font-family: sans-serif;
			font-size: 15px;
			padding-left: 15px;
			font-weight: 100;
			border: none;
		}
		.main-form button{
			width: 30%;
			height: 42px;
			font-family: sans-serif;
			font-size: 15px;
			padding-left: 15px;
			font-weight: 100;
			background-color: #6dc77a;
			color: #ffffff;
			border: none;
		}
		#feature-section{
			padding-top: 100px;
		}
		.feature-section-title{
			width: 70%;
			text-align: center;
			font-weight: 200;
			line-height: 1.5em;
			margin: auto;
		}
		.feature-content{
			margin: auto;
			width: 80%;
			text-align: center;
			padding-top: 100px;
		}
		.feature-content .col-3 p{
			font-size: .9em;
			letter-spacing: 1px;
		}
		.feature-content .col-3{
			padding: 10px;
			width: 30%;
		}
		.col-2{
			float: left;
			width: 48%;
		}
		#showcase1-container{
			padding-top: 60px;
			background-color: #f6f8fa;
			width: 100%;
			clear: both;
		}
		.showcase{
			width: 80%;
			margin: auto;
			overflow: auto;
		}
		.showcase1pic{
			width: 80%;
		}
		.feature-text{
			padding-top: 100px;
			
		}
		.section-title{
			width: 70%;
			margin: auto;
			font-weight: 200;
			line-height: 1.5em;
		}
		.section-left{
			width: 70%;
			padding: 20px 10px 10px 10px;
			margin: auto;
		}
		#showcase2-container{
			padding-top: 60px;
			padding-bottom: 10px;
			background-color: #ffffff;
			width: 100%;
			clear: both;
		}
		.col-1{
			width: 80%;
			margin: auto;
		}
		#call-to-action{
			background-image: url("cover image3.jpg");
		}
		.action-title{
			font-size: 4em;
			font-weight: 300;
			color: #ffffff;
			text-align: center;
			margin-top: 0;
			padding-top: 100px;
		}
		.col-1 p{
			font-size: 1.6em;
			font-weight: 300;
			color: #ffffff;
			text-align: center;
			margin: 0;
			padding-bottom: 100px;
		}
		.signupBTN{
			background-color: #6dc77a;
			color: #ffffff;
			font-size: 1em;
			font-weight: 200;
			text-decoration: none;
			padding: 30px 90px;
		}
		.signupBTN:hover{
			background-color: #5cbf2a;
		}
		.signupform{
			background-color: #f6f8fa;
			margin-right: 260px;
			padding: 0px 50px 10px 50px;
		}
		.signupform h6{
			color: black;
			padding-top: 15px;
			font-size: .9em;
			text-align: center;
		}
		.top-margin{
			margin-top: 100px;
			margin-left: 100px;
		}
		input{
			margin: 0;
			width: 100%;
			height: 50px;
			font-family: sans-serif;
			font-size: 15px;
			font-weight: 100;
			border: none;
			margin-top: 15px;
		}
		button{
			width: 100%;
			height: 50px;
			font-family: sans-serif;
			font-size: 15px;
			font-weight: 100;
			margin: 0;
			background-color: #6dc77a;
			color: #ffffff;
			border: none;
			margin-top: 15px;
		}
		footer{
			clear: both;
			height: 500px;
			background-image: url("footer image.jpg");
			background-position: 100% 100%;
		}
		.social-footer{
			width: 33%;
			float: left;
			height: 40%;
		}
		.social-footer:hover{
			background-color: #ffffff;
			opacity: .5;
		}
		.center{
			width: 50px;
			margin: auto;
			padding-top: 60px;
		}
		.copyright{
			font-size: .9em;
			text-align: center;
			display: block;
			padding-top: 15px;
		}

	</style>
</head>
<body>
	<header>
		<div id="header-container">
			<div class="col-3">
				<img class="logo" src="Naruto/Anime-waver.png" height="65" width="140">
			</div>
			<div class="col-3">
				<nav>
					<ul class="menu">
						<li>Home</li>
						<li>Features</li>
						<li>About</li>
						<li>Signup</li>
					</ul>
				</nav>
			</div>
			<div class="col=3">
				<a href="#" class="getStartedBTN">Get Started</a>
			</div>
		</div>
	</header>
	<div class="main-container">
		<div id="top-section-main">
			<div id="top-section-content">
				<h1>A Place Where Someone Still Thinks of You</h1>
				<img class="play-button" src="Naruto/play-button.png" alt="play-button" height="100px" width="100px">
				<div class="main-form">
					<form>
						<h6>SIGN UP FOR A FREE TRAIL</h6>
						<input type="text" name="name" placeholder="Enter Your Name">
						<input type="email" name="email" placeholder="Email-Adderess">
						<button style="trial" type="submit" value="submit">Start Free Trail</button>
					</form>
				</div>
			</div>
		</div>
		<div id="feature-section">
			<h1 class="feature-section-title">Anime waver is an amazing landing page brought to you on everyone's favorite <span style="background-color: #6dc77a; color: #ffffff; padding: 2px;">Anime</span> webpage platform.</h1>
			<div class="feature-content">
				<div class="col-3">
					<img style="width: 100%;" src="Naruto/new image1.png">
					<h3>Roy Mustang</h3>
					<p>"The world isn't perfect. But it's there for us, doing the best it can...that's what makes it so damn beautiful."</p>
				</div>
				<div class="col-3">
					<img style="width: 100%" src="Naruto/1212568.jpg">
					<h3>Armin Arlert</h3>
					<p>"People, who can’t throw something important away, can never hope to change anything."</p>
				</div>
				<div class="col-3">
					<img style="width: 100%" src="Naruto/new image2.png">
					<h3>Shintaro Midorima</h3>
					<p>"Don’t give up, there’s no shame in falling down! True shame is to not stand up again!"</p>
				</div>
			</div>
		</div>
		<div id="showcase1-container">
			<div class="showcase">
				<div class="col-2">
					<img class="showcase1pic" src="Naruto/naruto.jpg">
				</div>
				<div class="col-2">
					<div class="feature-text">
						<h1 class="section-title">Naruto Uzumaki</h1>
						<p class="section-left">"If you don't like your destiny, don't accept it<br>
						Instead, have the courage to change it the way you want it to be!"<br><br>
						Naruto Uzumaki is a fictional character in the manga and anime franchise Naruto, created by Masashi Kishimoto. Serving as the eponymous protagonist of the series, he is a young ninja from the fictional village of Konohagakure.</p>
					</div>
				</div>
			</div>
		</div>
		<div id="showcase2-container">
			<div class="showcase">
				<div class="col-2">
					<div class="feature-text">
						<h1 class="section-title">Sasuke Uchiha</h1>
						<p class="section-left">"Tears and rain, fall down on my face, my body is unable to stay yet my heart is unwilling to leave."<br><br>
						Sasuke Uchiha is a fictional character in the Naruto manga and anime franchise created by Masashi Kishimoto. Sasuke belongs to the Uchiha clan, a notorious ninja family, and one of the most powerful, allied with Konohagakure.</p>
					</div>
				</div>
				<div class="col-2">
					<img class="showcase1pic" src="Naruto/sasuke.jpg">
				</div>
			</div>
		</div>
		<div id="call-to-action">
			<div class="showcase">
				<div class="col-1">
					<h1 class="action-title">What are you waiting for?</h1>
					<p>Get started today and try for free - No credit card required</p>
					<p style="text-align"><a href="#" class="signupBTN">Try Today</a></p>
				</div>
			</div>
		</div>
		<div class="signup">
			<div class="col-2">
				<div class="top-margin">
					<h1 class="section-title" style="text-align: left;">Here what our fans have to say awesome</h1>
					<p class="section-left" style="font-style: italic;">"Anime-Waver is an amazing webpage for weeb to view their thoughts. I couldn't be happier!"<br><br><strong>-John Smith</strong></p>
				</div>
			</div>
			<div class="col-2">
				<form class="signupform">
					<h6>SIGN UP FOR A FREE 30 DAY TRAIL</h6>
					<input type="text" name="name" placeholder="Enter Your Name"><br>
					<input type="email" name="email" placeholder="Email-Adderess"><br>
					<button style="trail" type="submit" value="submit">Start Free Trail</button>
					<p style="font-size: 11px;">We don't share your personal info with anyone. Check out our <a href="#">Privacy Policy</a> for more information.</p>				
				</form>
			</div>
		</div>
	</div>
	<footer>
		<div class="social-footer">
			<div class="center">
				<img src="Naruto/twitter.png" alt="twitter" height="52" width="52">
			</div>
		</div>
		<div class="social-footer">
			<div class="center">
				<img src="Naruto/facebook.png" alt="twitter" height="52" width="52">
			</div>
		</div>
		<div class="social-footer">
			<div class="center">
				<img src="Naruto/instagram.png" alt="twitter" height="52" width="52">
			</div>
		</div>
		<h3 style="text-align: center; padding-top: 400px; color: black;">Anime-Waver</h3>
		<span class="copyright">&copy; Copyright 2020 Anime waver - Made with &hearts; Anime Weeb</span>
	</footer>
</body>
</html>
