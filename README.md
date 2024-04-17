# Embed-Code-Examples



<!DOCTYPE html>
<html>
<head>
	<title>

	</title>
	<meta name="viewport" content="width=device-width, 
				initial-scale=1.0">
	<style>

body {
		background-color: #E9E9E9;
		color: #333;
		font-family:"Lucida handwriting", "Snell Roundhand", "Helvetica Neue",Arial,Helvetica,sans-serif;
		font-size: 16px;
	}
	
	.amp {
		font-family:Garamond,Baskerville,Georgia,serif !important;
		font-style:italic;
		font-weight:normal;
		border: none;
	}
	
	a.polaroid {
		display: block;
		text-decoration: none;
		color: #333;
		padding: 10px 10px 20px 10px;
		width: 150px;
		border: 1px solid #BFBFBF;
		background-color: white;
		z-index: 2;
		font-size: 0.7em;
		-webkit-box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		-moz-box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		-webkit-transition: -webkit-transform 0.5s ease-in;
	}
	a.polaroid:hover,
	a.polaroid:focus,
	a.polaroid:active {
		z-index: 999;
		border-color: #6A6A6A;
		-webkit-box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		-moz-box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		-webkit-transform: rotate(0deg);
		-moz-transform: rotate(0deg);
		transform: rotate(0deg);
	}
	.polaroid img {
		margin: 0 0 15px;
		width: 150px;
		height: 150px;
	}
	
	a img {
		border: none;
		display: block;
	}
	
	.photo-album {
		position: relative;
		width: 80%;
		margin: 0 auto;
		max-width: 70em;
		height: 450px;
		margin-top: 5em;
		min-width: 800px;
		max-width: 900px;
	}
	.photo-album .polaroid {
		position: absolute;
	}
	.photo-album h1 {
		position: absolute;
		z-index: 5;
		top: 150px;
		text-align: center;
		width: 100%;
		line-height: 1.9;
	}
	.photo-album h1 span {
		background-color: white;
		font-family: "Helvetica Neue",Arial,Helvetica,sans-serif;
		padding: 0.4em 0.8em 0.3em 0.8em;
		-webkit-box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		-moz-box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		box-shadow: 2px 2px 4px rgba(0,0, 0, 0.3);
		border: 1px solid #6A6A6A;
	}
	.photo-album .small {
		width: 75px;
		padding: 6px 6px 12px 6px;
		font-size: 0.6em;
	}
	.photo-album .small img {
		width: 75px;
		height: 75px;
	}
	.photo-album .medium {
		width: 200px;
		padding: 13px 13px 26px 13px;
		font-size: 0.8em;
	}
	.photo-album .medium img {
		width: 200px;
		height: 200px;
	}
	.photo-album .large {
		width: 300px;
		padding: 20px 20px 30px 20px;
		font-size: 1em;
	}
	.photo-album .large img {
		width: 300px;
		height: 300px;
	}
	.photo-album .img1 {
		bottom: 10px;
		right: 365px;
		-webkit-transform: rotate(10deg);
		-moz-transform: rotate(10deg);
		transform: rotate(10deg);
	}
	.photo-album .img2 {
		top: 50px;
		right: 20px;
		-webkit-transform: rotate(-4deg);
		-moz-transform: rotate(-4deg);
		transform: rotate(-4deg);
	}
	.photo-album .img3 {
		left: 400px;
		top: 0;
		-webkit-transform: rotate(-5deg);
		-moz-transform: rotate(-5deg);
		transform: rotate(-5deg);
	}
	.photo-album .img4 {
		top: 10px;
		left: 495px;
		-webkit-transform: rotate(-20deg);
		-moz-transform: rotate(-20deg);
		transform: rotate(-20deg);
	}
	.photo-album .img5 {
		bottom: 0;
		right: 0;
		-webkit-transform: rotate(1deg);
		-moz-transform: rotate(1deg);
		transform: rotate(1deg);
	}
	.photo-album .img6 {
		bottom: 10px;
		right: 156px;
		-webkit-transform: rotate(6deg);
		-moz-transform: rotate(6deg);
		transform: rotate(6deg);
	}
	.photo-album .img7 {
		bottom:0;
		left:400px;
		-webkit-transform: rotate(-10deg);
		-moz-transform: rotate(-10deg);
		transform: rotate(-10deg);
	}
	.photo-album .img8 {
		bottom: -20px;
		left: 700px;
		-webkit-transform: rotate(-8deg);
		-moz-transform: rotate(-8deg);
		transform: rotate(-8deg);
	}
	.photo-album .img9 {
		bottom: 0;
		left: 0;
		-webkit-transform: rotate(-8deg);
		-moz-transform: rotate(-8deg);
		transform: rotate(-8deg);
	}
	.photo-album .img10 {
		top: 0;
		left: 20px;
		-webkit-transform: rotate(8deg);
		-moz-transform: rotate(8deg);
		transform: rotate(8deg);
	}
	.photo-album .img11 {
		top: 0;
		right: 0;
		-webkit-transform: rotate(-8deg);
		-moz-transform: rotate(-8deg);
		transform: rotate(-8deg);
	}
	.photo-album .img12 {
		top: 0;
		left: 680px;
		-webkit-transform: rotate(18deg);
		-moz-transform: rotate(18deg);
		transform: rotate(18deg);
	}
	.photo-album .img13 {
		bottom: -20px;
		right: 630px;
		-webkit-transform: rotate(4deg);
		-moz-transform: rotate(4deg);
		transform: rotate(4deg);
	}
	.photo-album .img14 {
		top: 90px;
		left: 430px;
		-webkit-transform: rotate(15deg);
		-moz-transform: rotate(15deg);
		transform: rotate(15deg);
	}
	.photo-album .img15 {
		left:176px;
		top:20px;
		-webkit-transform: rotate(-8deg);
		-moz-transform: rotate(-8deg);
		transform: rotate(-8deg);
	}
	
	a:hover,
	a:focus {
		z-index: 5;
	}
	


	</style>
</head>


<body>

	<div class="photo-album">
		
		<h1><span>I Shoot My Happiness</span></h1>
		
		<a href="https://drive.google.com/file/d/1bu0kJKejQv6NMAg6ZWUeD3fji-4ocsk2/view?usp=drive_link" class="large polaroid img1"><img src="https://drive.google.com/thumbnail?id=1bu0kJKejQv6NMAg6ZWUeD3fji-4ocsk2" alt="Page Image">This breathtaking volcanic lake is at Wai-O-Tapu Thermal Wonderland</a>





		<a href="https://drive.google.com/file/d/195mxH-SKZOPmLUuct3ybBGBfQ70rVKXz/view?usp=drive_link" class="polaroid img2"><img src="https://drive.google.com/thumbnail?id=195mxH-SKZOPmLUuct3ybBGBfQ70rVKXz" alt="Page Image">This breathtaking volcanic lake is at Wai-O-Tapu Thermal Wonderland</a>


		<a href="https://drive.google.com/file/d/1PR3bEnZkch_wSyo9hrHfwL7Jd0tDOmnb/view?usp=drive_link" class="small polaroid img3"><img src="https://drive.google.com/thumbnail?id=1PR3bEnZkch_wSyo9hrHfwL7Jd0tDOmnb" alt="Page Image">This breathtaking volcanic lake is at Wai-O-Tapu Thermal Wonderland</a>

		
		<a href="https://drive.google.com/file/d/1agXNHyS5fxzs0fVcB9yWsOHT0Buns87e/view?usp=drive_link" class="medium polaroid img4"><img src="https://drive.google.com/thumbnail?id=1agXNHyS5fxzs0fVcB9yWsOHT0Buns87e" alt="">At Kaikoura we went whale watching!</a>
		
		<a href="https://drive.google.com/file/d/1refwsFC5BWX3sN2Gem9SfLMBa-RGfS_C/view?usp=drive_link" class="polaroid img5"><img src="https://drive.google.com/thumbnail?id=1refwsFC5BWX3sN2Gem9SfLMBa-RGfS_C" alt="">Found this little cutie on a walk in New Zealand!</a>
		
		<a href="https://drive.google.com/file/d/1lxqagZ-9IJ52Z4NzfA70eqBqgg76uNSF/view?usp=drive_link" class="polaroid img6"><img src="https://drive.google.com/thumbnail?id=1lxqagZ-9IJ52Z4NzfA70eqBqgg76uNSF" alt="">An amazing bubbling volcanic spring, a bit muddy</a>

		
		<a href="https://drive.google.com/file/d/1nYs9_mSFW9c2LYCf7dSAkhBoozm5rI3e/view?usp=drive_link" class="polaroid img7"><img src="https://drive.google.com/thumbnail?id=1nYs9_mSFW9c2LYCf7dSAkhBoozm5rI3e" alt="">Simon in a giant Kiwi, pretending to be a Kiwi (the bird)</a>


		<a href="https://drive.google.com/file/d/1TFxF8e8I3Cgs8dhSjxRxLMk9S_SkTBDc/view?usp=drive_link" class="small polaroid img8"><img src="https://drive.google.com/thumbnail?id=1TFxF8e8I3Cgs8dhSjxRxLMk9S_SkTBDc" alt="">Albatross in Dunedin</a>


		<a href="https://drive.google.com/file/d/1pXlVhLEQevaxNRjxcv-KmeqNxKJuaUGJ/view?usp=drive_link" class="medium polaroid img9"><img src="https://drive.google.com/thumbnail?id=1pXlVhLEQevaxNRjxcv-KmeqNxKJuaUGJ" alt="">I U T - The Read Heaven</a>








		<a href="https://drive.google.com/file/d/1AdjJ29LdPQxNfpHRsezjD469qmiZIA9v/view?usp=drive_link" class="polaroid img10"><img src="https://drive.google.com/thumbnail?id=1AdjJ29LdPQxNfpHRsezjD469qmiZIA9v" alt="">Kanaia Bridge Tour</a>


		<a href="https://drive.google.com/file/d/1lQZZMhC2xYjG8diHO6041RtCmG_GCzr7/view?usp=drive_link" class="small polaroid img11"><img src="https://drive.google.com/thumbnail?id=1lQZZMhC2xYjG8diHO6041RtCmG_GCzr7" alt="">Sulphurous</a>



		<a href="https://drive.google.com/file/d/1t1qhOwAreU4ffvAQwru_DjLFWhhSdmzW/view?usp=drive_link" class="small polaroid img12"><img src="https://drive.google.com/thumbnail?id=1t1qhOwAreU4ffvAQwru_DjLFWhhSdmzW" alt="">Sea lions!</a>












		<a href="https://drive.google.com/file/d/1ZfwWNBSFsBYZKsldGr1u04MR5lPOLvzv/view?usp=drive_link" class="small polaroid img13"><img src="https://drive.google.com/thumbnail?id=1jpb2BiqksIMZJq0lUgVlaVUnT7Ea7iMQ" alt="">Short Story Writing</a>








		<a href="https://drive.google.com/file/d/1ZfwWNBSFsBYZKsldGr1u04MR5lPOLvzv/view?usp=drive_link" class="small polaroid img14"><img src="https://drive.google.com/thumbnail?id=1ZfwWNBSFsBYZKsldGr1u04MR5lPOLvzv" alt="">Stewart Island</a>










		<a href="https://drive.google.com/file/d/1lu7hBDW7nnQrYuIO3W1nh_ivplXekXZR/view?usp=drive_link" class="polaroid img15"><img src="https://drive.google.com/thumbnail?id=1lu7hBDW7nnQrYuIO3W1nh_ivplXekXZR" alt="">Us in a blue cave on the Franz Josef glacier</a>

	</div>
	

</body>
</html>
