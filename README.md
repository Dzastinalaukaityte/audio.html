# audio.html

<!DOCTYPE html>
<html lang="en">
<meta charset="utf-8">
<head>
	<title>Media/embedding: Task 1</title>
	<link rel="stylesheet" type="text/css" href="3style.css">
</head>
<body>
	<h1>Basic audio embed</h1>
	<audio src="mediasamples\sample_audio.mp3" type="audio/mpeg" controls="true" loop="true" autoplay="true"><code>audio</code>
	<p>Your browser doesn't support HTML5 audio. Here is a <a href="sample_audio.mp3">link to the audio</a> instead.</p>
	</audio>
</body>
</html>


(3STYLE.CSS)

body {
	background-color: #fff;
	color: #333;
	font: 1em / 1.4 Helvetica Neue, Helvetica, Arial, sans-serif;
	padding: 1em;
	margin: 0;
}

* {
	box-sizing: border-box;
}

audio {
	border: 1px solid black;
}
