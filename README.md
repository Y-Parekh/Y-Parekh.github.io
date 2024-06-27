<html>
<head>
<style>
	body{background-color: black;}
	
	h1 {font-soze: 20pt;
		  color:Brown;
		  font-family: Goudy Stout;}
	p {font-size: 15pt;
		font family: Kristen ITC;}
	img{
		border-radius: 50%;
		}
</style>
	
</head>

<body>
	<script>
		var cities = ["Delhi", "Bengaluru", "Visakhapatnam", "Hyderabad", "Lucknow", "Ahmedabad", "Indore", "Pune", "Bhopal", "Surat", "Meerut", "Mumbai", "Chennai", "Warangal"];
		var text = "";
		var i;
		for (i = 0; i < cheese.length; i++) {
			text += getRandomItem(cities) + " " + cities[i] + "<br>";
		}
		
		document.write(text)
	</script>
	
	<p> Click the button to loop whilst i is less than 10. </p>
	<button onclick ="whileLoop()"> Click Me! </button>
	<p id="While_Loop"></p>
	
	<script>
	 function whileLoop() {
		var outputtext = "";
		var i = 0;
		while (i < 10) {
			outputtext += "<br> The number is " + i;
				i++;
			}
		chosenElement = document.getElementById("While_Loop");
		chosenElement.innerHTML = outputtext;
		}
	var x=3;
	switch(x) {
	case 1:
		text = "x equals 1";
	case 2:
		text = "x equals 2";
	case 3:
		text = "x equals 3";
		break;
	}
	document.write(text)
	str = "Please visit London!";
	var x = str.replace(/London/g, "Mumbai");
	document.write("<br>", x);
	
	
	
	</script>
	<p id="functions_example"></p>
	<script>
			function myFunction(a,b) {
					return a*b
					}
			chosenElement = document.getElementById("functions_example")
			chosenElement.innerHTML = myFunction(10,5)
	</script>
	
	<form>
		Enter your Number here:
		<br>
		<input id="inpt" type="number" name="value";
		<br>
		<button type="button" onclick="myFunction()">ClickMe!<button>
	</form>
	
	<script>
		function myFunction(){
			var x = document.getElementById("inpt").value;
			y = x * x;
			document.write(y);
			}
	</script>
	
	<h1><strong><u>Paneer</strong></u></h1>
	<p> This page is all about Paneer	</p>
	<img src = "https://media.cntraveller.in/wp-content/uploads/2020/05/homemade-paneer-recipes-1366x768.jpg">
	<li><a href="https://en.wikipedia.org/wiki/Paneer">PANEEERRRRRRRRRRRR PLS CLICK</a></li>
	
</body>

</html>
