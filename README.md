# new
<html>

<head>
	<title>Assignment Solution for Module 2</title>
	<meta charset = "utf-8">
	<meta name = "viewport" content = "width = device-width, initial-scale = 1">
	<link rel = "stylesheet" href = "cssass.txt"/>
</head>

<body>
	<h1> Our Menu </h1>
	<div class = "row">
		<div class = "col-lg-4 col-md-6 col-sm-12">
			<section>
				<h3 id = "t1"> Chicken </h3>
				<p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. </p>
			</section>
		</div>
		<div class = "col-lg-4 col-md-6 col-sm-12">
			<section>
				<h3 id = "t2"> Beef </h3>
				<p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. </p>
			</section>
		</div>
		<div class = "col-lg-4 col-md-12 col-sm-12">
			<section>
				<h3 id = "t3"> Shushi </h3>
				<p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. </p>
			</section>
		</div>
	</div>
</body>
</html>


#cssass.txt
* {
			box-sizing : border-box;
			margin: 0;
			padding: 0;
		}

		h1 {
			margin-top: 50px;
			margin-bottom: 20px;
			text-align: center;
		}

		section {
			border: 1px solid black;
			background-color: grey;
			margin: 10px;
		}

		.row {
			width: 100%;
		}

		h3 {
			border-left: 1px solid black;
			border-bottom: 1px solid black;
			width: 150px;
			text-align: center;
			float: right;
			font-size: 24px;
		}

		#t1 {
			background-color: red;
		}

		#t2 {
			background-color: blue;
		}

		#t3 {
			background-color: yellow;
		}

		p {
			padding: 15px 15px 15px 15px;
			font-family: Helvetica;
			color: black;
			clear: right;
		}

@media (min-width: 992px){
	.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-10, .col-lg-11, .col-lg-12{
		float: left;
	}
	.col-lg-1{
		width: 8.33%;
	}
	.col-lg-2{
		width: 16.66%;
	}
	.col-lg-3{
		width: 25%;
	}
	.col-lg-4{
		width: 33%;
	}
	.col-lg-5{
		width: 41.66%;
	}
	.col-lg-6{
		width: 50%;
	}
	.col-lg-7{
		width: 58.33%;
	}
	.col-lg-8{
		width: 66.66%;
	}
	.col-lg-9{
		width: 74.99%;
	}
	.col-lg-10{
		width: 83.33%;
	}
	.col-lg-11{
		width: 91.66%;
	}
	.col-lg-12{
		width: 100%;
	}
}

@media (min-width: 768px) and (max-width: 991px){
	.col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-10, .col-md-11, .col-md-12{
		float: left;
	}
	.col-md-1{
		width: 8.33%;
	}
	.col-md-2{
		width: 16.66%;
	}
	.col-md-3{
		width: 25%;
	}
	.col-md-4{
		width: 33%;
	}
	.col-md-5{
		width: 41.66%;
	}
	.col-md-6{
		width: 50%;
	}
	.col-md-7{
		width: 58.33%;
	}
	.col-md-8{
		width: 66.66%;
	}
	.col-md-9{
		width: 74.99%;
	}
	.col-md-10{
		width: 83.33%;
	}
	.col-md-11{
		width: 91.66%;
	}
	.col-md-12{
		width: 100%;
	}
}

@media (max-width: 767px){
	.col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-lsm-10, .col-sm-10, .col-sm-11, .col-sm-12{
		float: left;
	}
	.col-sm-1{
		width: 8.33%;
	}
	.col-sm-2{
		width: 16.66%;
	}
	.col-sm-3{
		width: 25%;
	}
	.col-sm-4{
		width: 33%;
	}
	.col-sm-5{
		width: 41.66%;
	}
	.col-sm-6{
		width: 50%;
	}
	.col-sm-7{
		width: 58.33%;
	}
	.col-sm-8{
		width: 66.66%;
	}
	.col-sm-9{
		width: 74.99%;
	}
	.col-sm-10{
		width: 83.33%;
	}
	.col-sm-11{
		width: 91.66%;
	}
	.col-sm-12{
		width: 100%;
	}
}

