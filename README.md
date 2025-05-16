<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Traveler</title>
	<style>
		* {
	margin: 0;
	padding: 0;
}

.container {
	width: 1519px;
	height: 3050px;
	margin: 0 auto;
	background: red;
	font-family: "Montserrat";
}

.top__section {
	width: 100%;
	height: 700px;
	background-image: url("/bg.png");
	background-size: 100% 100%;
	background-repeat: no-repeat;
	background-position: center;
	padding-top: 15px;
}

.header {
	width: 100%;
	height: 80px;
}

.header__row {
	width: 80%;
	height: 80px;
	margin: 0 auto;
}

.header__logo {
	width: 20%;
	height: 80px;
	float: left;
}

.logo {
	font-size: 35px;
	line-height: 80px;
	color: #fff;
	font-weight: 600;
}

.header__menu {
	width: 40%;
	height: 80px;
	float: left;
	margin-left: 120px;
}

.menu {
	width: 70%;
	height: 80px;
	margin: 0 auto;
}

.menu__link {
	line-height: 80px;
	float: left;
	margin-right: 40px;
	list-style: none;
}

.menu__link a {
	font-size: 16px;
	color: #fff !important;
	text-decoration: none;
	transition: all .4s;
	display: block;
}

.menu__link:hover a {
	transform: scale(1.1);
}

.header__user{
	width: 30%;
	height: 80px;
	float: right;
}

.header__user img {
	width: 25px;
	height: 25px;
	float: left;
	margin-top: 28px;
	margin-left: 240px;
}

.user__text {
	font-size: 20px;
	color: #fff;
	font-weight: 500;
	float: left;
	line-height: 80px;
	margin-left: 10px;
	cursor: pointer;
	margin-right: 0px;
}

/*hr{
	width: 20px;
	float: left;
	line-height: 80px;
	color: orange;
	transform: translateY(8px);
}*/
.intruduction{
	width: 100%;
	height: 50%;
/*	background: green;*/
	margin-top: 180px;
}
.intruduction__row{
	width: 80%;
	height: 100%;
/*	background: purple;*/
	margin: 0 auto;
}
.intruduction__subtitle {
	float: left;
	color: white;
/*	background: red;*/
}

.subtitle__line {
	float: left;
	color: orange;
	font-weight: 900;
	margin-right: 5px;
	transform: translateY(-5px);
}

.subtitle__text {
	float: left;
	color: orange;
	font-size: 20px;
}
.intruduction__explore{
	width: 400px;
	height: 200px;
/*	background: red;*/
	position: absolute;
	top: 300px;
}
.explore__text{
	
	position: absolute;
	top:315px;
	color: #fff;
	font-size: 60px;
}
.intruduction__logo{
	width: 180px;
	height: 50px;
/*	background: orange;*/
	position: absolute;
	top: 470px;
	float: left;
}
.logo__text{
	float: left;
	font-size: 20px;
	color: #fff;
	position: absolute;
	top: 470px;

}
.intruduction__logo img{
	position: absolute;
	left: 125px
}
.medium__section{
	width: 100%;
	height: 2000px;
	background: #171717;
	position: relative;
}
.section__top{
	width: 80%;
	height: 400px;/*
	background: blue;*/
	position: absolute	;
	top: 150px;
	left: 145px;
}
.top__row1{
	width: 50%;
	height: 400px;
	float: left;
/*	background: purple;*/
}
.top__row2{
	width: 50%;
	height: 400px;
	float: right;/*
	background: green;*/
}
.top__row2   img{
	width: 400px;
	height: 100%px;
	float: right;
	position: relative;
}
.row1__line{
	float: left;
	color: orange;
	font-weight: 900;
	margin-right: 5px;  
	transform: translateY(-5px);	
}
.row1__text{
	float: left;
	color: orange;
	font-size: 20px;	
}
.row1__travel{
	margin-top: 30px;	
	color: #fff;
	font-size: 60px;	
}
.row1__lorem{
	margin-top: 10px;
	color: #fff;
	line-height: 35px;
	font-size: 18px;
}
.row1__text2{
	float: left;
	color: orange;
	font-size: 20px;
	margin-top: 15px;	
}
.top__row1 img{
	margin-top: 20px;
	margin-left: 15px;
}
.section__medium{
	width: 80%;
	height: 400px;
/*	background: blue;*/
	position: absolute;
	top: 800px;
	left: 145px;
}
.medium__row3{
	width: 50%;
	height: 400px;
	float: left;
}
.medium__row3 img{
	width: 400px;
	height: 100%px;
	float: left;
	position: relative;
}
.medium__row4{
	width: 50%;
	height: 400px;
	float: left;
}
.row4__line{	
	float: left;
	color: orange;
	font-weight: 900;
	margin-right: 5px;
	transform: translateY(-5px);
}
.row4__text{
	float: left;
	color: orange;
	font-size: 20px;	
}
.row4__travel{
	margin-top: 30px;	
	color: #fff;
	font-size: 60px;
}
.row4__lorem{
	margin-top: 10px;
	color: #fff;
	line-height: 35px;
	font-size: 18px;
}
.row4__text2{
	float: left;
	color: orange;
	font-size: 20px;
	margin-top: 15px;
}
.medium__row4 img{
	margin-top: 20px;
	margin-left: 15px;
}
.section__bottom{
	width: 80%;
	height: 400px;
/*	background: blue;*/
	position: absolute;
	top: 1500px;
	left: 145px;
}
.bottom__row5{
	width: 50%;
	height: 400px;
	float: left;
/*	background: purple;*/
}
.bottom__row6{
	width: 50%;
	height: 400px;
	float: right;/*
	background: green;*/
}
.bottom__row6 img{
	width: 400px;
	height: 100%px;
	float: right;
	position: relative;
}
.row5__line{
	float: left;
	color: orange;
	font-weight: 900;
	margin-right: 5px;
	transform: translateY(-5px);	
}
.row5__text{
	float: left;
	color: orange;
	font-size: 20px;	
}
.row5__travel{
	margin-top: 30px;	
	color: #fff;
	font-size: 60px;	
}
.row5__lorem{
	margin-top: 10px;
	color: #fff;
	line-height: 35px;
	font-size: 18px;
}
.row5__text2{
	float: left;
	color: orange;
	font-size: 20px;
	margin-top: 15px;	
}
.bottom__row5 img{
	margin-top: 20px;
	margin-left: 15px;
}
.bottom__section{
	width: 100%;
	height: 350px;
	background: black;
	position: relative;
}
.section__travel{
	width: 80%;
	height: 230px;
/*	background: purple;*/
	position: absolute;
	top: 30px;
	left: 145px;
	float: left;
}
.travel__left{
	width: 50%;
	height: 100%;
/*	background: blue;*/
	float: left;
}
.logo2 {
	font-size: 40px;
	line-height: 80px;
	color: #fff;
	font-weight: 600;
}
.left__text{
	margin-top: 10px;
	color: #fff;
	line-height: 20px;
	font-size: 18px;
}
.travel__center{
	width: 30%;
	height: 100%;
	float: left;
/*	background: red;*/
}
.center__text1{
	float: left;
	color: orange;
	font-size: 20px;
	margin-top: 15px;
}
.center__text2{
	position: absolute;
	top: 45px;
	color: #fff;
	line-height: 35px;
	float: left;
	font-size: 18px;
}
.travel__right{
	width: 20%;
	height: 100%;
	float: left;
/*	background: green;*/
}
.right__text1{
	float: left;
	color: orange;
	font-size: 20px;
	margin-top: 15px;
}
.right__text2{
	position: absolute;
	top: 45px;
	color: #fff;
	line-height: 40px;
	float: left;
	font-size: 18px;
}
.right__logo{
	width: 100px;
	height: 30px;
	position: absolute;
	top: 190px;
/*	background: blue;*/
}
.logo__left{
	width: 50px;
	height: 30px;
	float: left;
/*	background: red;*/
}
.logo__left img{	
	width: 30px;
	height: 30px;
	float: left;
}
.logo__right{
	width: 50px;
	height: 30px;
	float: left;
/*	background: purple;*/
}
.logo__right img{
	width: 30px;
	height: 30px;
	float: right;	
}
.section__travel2{
	width: 20%;
	height: 26px;
	float: left;
	position: absolute;
	top: 300px;
	left: 50px;
/*	background: blue;*/
}
.travel2__text{
	color: #898989;
}



	</style>
</head>
<body>
	<div class="container">
		<div class="top__section">
			<div class="header"> 
                   <div class="hero">
                        <!-- <img src="/bg.png" alt=""> -->
                        </div>
				<div class="header__row">
					<div class="header__logo">
						<p class="logo">
							TRAVELER
						</p>
					</div>
                
                      
					<div class="header__menu">
                        
						<ul class="menu">
							<li class="menu__link"><a href="#">Travel Guide</a></li>
							<li class="menu__link"><a href="#">About Us</a></li>
							<li class="menu__link"><a href="#">Blog</a></li>	 
						</ul>
					</div>
					<div class="header__user">
						<img src="user.png">
						<p class="user__text">Account</p>
					</div>
				</div>
			</div>
			<div class="intruduction">
				<div class="intruduction__row">
					<p class="intruduction__subtitle">
						<p class="subtitle__line">		
							_____
						</p>
						<p class="subtitle__text">
							WELCOME
						</p> 
					</p>
					<p class="intruduction__explore">
						<p class="explore__text">
							Explore New Horitzons<br>
							& Discover The world
						</p>
						<p class="intruduction__logo">
							<img src="Arrow 5.png">
							<p class="logo__text">
								scrool down 
							</p>
						</p>
					</p>
				</div>
			</div>
		</div>
		<div class="medium__section">
			<div class="section__top">
				<div class="top__row1">
					<p class="row1__line">		
						_____
					</p>
					<p class="row1__text">
						GET STARTED
					</p>
					<p class="row1__travel">
						What kind of <br> 
						traveler are you?
					</p>
					<p class="row1__lorem">
						Lorem ipsum dolor sit amet, consectetur adipiscing elit. Convallis <br>
						cursus vel sollicitudin massa. Sed accumsan congue porta donec <br>
						et, neque odio id adipiscing. Facilisis blandit sed faucibus massa <br>
						suspendisse rhoncus massa nulla. Ut id montes, enim vivamus. <br>
						Ut id montes, enim vivamus
					</p>
					<p class="row1__text2">
						read more 
					</p>
					<img src="Arrow 6.png">					
				</div>
				<div class="top__row2">
					<img src="unsplash_1Z2niiBPg5A.png">
				</div>
			</div>
			<div class="section__medium">
				<div class="medium__row3">
					<img src="unsplash_UVyOfX3v0Ls.png">					
				</div>
				<div class="medium__row4">
					
					<p class="row4__line">		
						_____
					</p>
					<p class="row4__text">
						HIKING ESSENTIALS
					</p>
					<p class="row4__travel">
						Picking the right <br>
						Hiking Gear!  
					</p>
					<p class="row4__lorem">
						Lorem ipsum dolor sit amet, consectetur adipiscing elit. Convallis <br>
						cursus vel sollicitudin massa. Sed accumsan congue porta donec <br>
						et, neque odio id adipiscing. Facilisis blandit sed faucibus massa <br>
						suspendisse rhoncus massa nulla. Ut id montes, enim vivamus. <br>
						Ut id montes, enim vivamus
					</p>
					<p class="row4__text2">
						read more 
					</p>
					<img src="Arrow 6.png">
				</div>
			</div>
			<div class="section__bottom">
				<div class="bottom__row5">
					<p class="row5__line">		
						_____
					</p>
					<p class="row5__text">
						WHERE YOU GO IS THE KEY
					</p>
					<p class="row5__travel">
						Understand Your  <br>
						Map & Timing 
						
					</p>
					<p class="row5__lorem">
						Lorem ipsum dolor sit amet, consectetur adipiscing elit. Convallis <br>
						cursus vel sollicitudin massa. Sed accumsan congue porta donec <br>
						et, neque odio id adipiscing. Facilisis blandit sed faucibus massa <br>
						suspendisse rhoncus massa nulla. Ut id montes, enim vivamus. <br>
						Ut id montes, enim vivamus
					</p>
					<p class="row5__text2">
						read more 
					</p>
					<img src="Arrow 6.png">					
				</div>
				<div class="bottom__row6">
					<img src="unsplash_lsoogGC_5dg.png">
				</div>
			</div>
		</div>
		<div class="bottom__section">
			<div class="section__travel">
				<div class="travel__left">
					<p class="logo2">
						TRAVELER
					</p>
					<p class="left__text">
						Get our there & discover your next <br>
						slope mountain & destionation
					</p>						
				</div>
				<div class="travel__center">
					<p class="center__text1">
						More on The Blog
					</p>
					<p class="center__text2">
						About MNTN <br>
						Contribubors & Writers <br>
						Write For Us <br>
						Contact Us <br>
						Privacy Policy					
					</p>

				</div>
				<div class="travel__right">
					<p class="right__text1">
						More on MNTN
					</p>
					<p class="right__text2">
						The team <br>
						JobsS <br>
						Press
					</p>
					<div class="right__logo">
						<div class="logo__left">
							<img src="Vector.png">
						</div>
						<div class="logo__right">
							<img src="Vector (1).png">
						</div>
					</div>
				</div>
			</div>
			<div class="section__travel2">
				<p class="travel2__text">Copyright @ 2021. Digitech with love</p>
			</div>
		</div>
	</div>
</body>
</html>
