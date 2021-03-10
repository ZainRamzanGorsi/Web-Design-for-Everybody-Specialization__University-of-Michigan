<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<style>
		body {
			margin: 2%;
			border: 1px solid black;
			background-color: #b3b3b3;
		}

		#images {
			line-height: 40px;
			width: 300px;
			height: 300px;
			border: 5px solid black;
			margin: 0 auto;
			background-color: #8e68ff;
			background-image: url('');
			background-repeat: no-repeat;
			color: #05200c;
			text-align: center;
			background-size: 100%;
			margin-bottom: 25px;
			font-weight: 70px;
		}

		.preview {
			width: 10%;
			margin-left: 17%;
			border: 10px solid black;
		}

		img {
			width: 95%;
		}
	</style>
</head>

<body>
	<div id="images">
		Hover over an image below to display here.
	</div>


	<!-- ----------------------------------------------------------- -->
	<img src="https://upload.wikimedia.org/wikipedia/commons/a/ac/Iqbal_Manzil_the_birthplace_of_Iqbal.JPG"
		alt="Allma Iqbal_Manzil_the_birthplace_of_Iqbal" class="preview" onmouseover="upDate(this)"
		onmouseout="unDo()">
	<!-- ----------------------------------------------------------- -->

	<img src="https://archaeology.punjab.gov.pk/system/files/1_29.jpg" alt="Allama Iqbal House" class="preview"
		onmouseover="upDate(this)" onmouseout="unDo()">
	<!-- ----------------------------------------------------------- -->

	<img src="https://i.dawn.com/2012/04/allama-iqbal-manzil-room-of-birth-mohsin-abbas-670.jpg"
		alt="Allama Iqbal House" class="preview" onmouseover="upDate(this)" onmouseout="unDo()">
	<!-- ----------------------------------------------------------- -->

	<img src="https://media-cdn.tripadvisor.com/media/photo-s/02/5d/82/39/alama-iqbal-house-entrance.jpg"
		alt="Allama Iqbal House" class="preview" onmouseover="upDate(this)" onmouseout="unDo()">
	<!-- ----------------------------------------------------------- -->

	<script>


		function upDate(element) {
			document.getElementById('images').innerHTML = element.alt;
			document.getElementById('images').style.backgroundImage = "url(" + element.src + ")";
		}

		function unDo(element) {
			document.getElementById('images').innerHTML = 'Hover over an image below to display here.';
			document.getElementById('images').style.backgroundImage = "url('')"
		}</script>
</body>

</html>
