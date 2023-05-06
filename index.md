<!DOCTYPE html>
<html>
<head>
	<title>CivMC</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<style>
		body {
			margin: 0;
			padding: 0;
			font-family: sans-serif;
		}
		header {
			position: relative;
			height: 100vh;
			background-image: url('minecraft-landscape.jpg');
			background-size: cover;
			background-position: center;
			background-attachment: fixed;
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: center;
		}
		#logo {
			position: absolute;
			top: 20px;
			left: 20px;
			width: 150px;
			height: 150px;
			background-image: url('civmc-logo.png');
			background-size: contain;
			background-repeat: no-repeat;
			background-position: center;
		}
		#tagline {
			color: white;
			font-size: 36px;
			text-align: center;
			text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
			margin: 0;
			padding: 0;
			margin-top: 20px;
			line-height: 1.2;
		}
		#tagline span {
			font-size: 24px;
			font-style: italic;
		}
		section {
			padding: 60px 0;
			text-align: center;
		}
		h1 {
			font-size: 36px;
			margin-bottom: 20px;
		}
		p {
			font-size: 20px;
			line-height: 1.5;
			max-width: 600px;
			margin: auto;
			margin-bottom: 40px;
		}
		#banner-images {
			display: flex;
			flex-wrap: wrap;
			align-items: center;
			justify-content: center;
			margin-bottom: 60px;
		}
		#banner-images img {
			width: 200px;
			height: 200px;
			object-fit: cover;
			margin: 10px;
			cursor: pointer;
			transition: transform 0.3s ease-in-out;
		}
		#banner-images img:hover {
			transform: scale(1.1);
		}
	</style>
</head>
<body>
	<header>
		<div id="logo"></div>
		<h1 id="tagline">CivMC<br>Building with more than just <span>blocks</span></h1>
	</header>
	<section>
		<h1>What is CivMC?</h1>
		<p>Placeholder text explaining what CivMC is. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris interdum, purus eu interdum bibendum, libero est eleifend lacus, quis convallis quam nisi et velit. Aliquam sit amet mollis lectus. Nunc tincidunt justo vel leo mollis, sed facilisis ipsum varius. Fusce vel magna non risus congue laoreet id eget ex.</p>
		<div id="banner-images">
			<a href="https://example.com"><img src="image1.jpg"></a>
			<a href="https://example.com"><img src="image2.jpg"></a>
      <a href="https://example.com"><img src="image3.jpg"></a>
      <a href="https://example.com"><img src="image4.jpg"></a>
      <a href="https://example.com"><img src="image5.jpg"></a>
      <a href="https://example.com"><img src="image6.jpg"></a>
</div>
</section>
</body>
</html>
