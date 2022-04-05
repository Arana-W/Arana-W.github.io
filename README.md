<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Positioning Elements</title>
	<style>

	* {
		box-sizing: border-box;
		margin: 0;
		padding: 0;
	}
	h1 {
		margin-bottom: 15px;
	}
	div#container {
		background-color: #00FFFF;/*CELESTE*/
		position: relative;
	} 
	p {
		width: 50px;
		height: 50px;
		border: 1px solid black;
		margin-bottom: 15px;
	}
	#p1 {
		background-color: #A52A2A;/*RED*/
		position: relative;
		top: 65px;
		left: 65px;
	}
	#p2 {
		background-color: #DEB887;/*MOSTAZA*/
	}
	#p3 {
		background-color: #5F9EA0;/*VERDE CEMENTO*/
		position: absolute;
		top: 0px;
		left: 0px;
	}
	#p4 {
		background-color: #FF7F50;/*ORANGE*/
	}
	</style>
	
</head>
<body>
<h1>Positioning Elements</h1>

<div id="container">
	<p id="p1"></p>
	<p id="p2"></p>
	<p id="p3"></p>
	<p id="p4"></p>
</div>

</body>
</html>
