<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Q4 Seatwork 2</title>
	<style type="text/css">
		
	</style>
</head>
<body>
	<center>
		<form class="form-group">
			<label id="num1">enter the first number</label><br>
			<input id="input1" type="Number" class="form-control" placeholder="Enter here">
			<label id="num3">enter the second number</label><br>
			<input id="input2" type="Number" class="form-control" placeholder="Enter here">
			<button id="button1" class="btn btn-success" onclick="add()">Add num1 and num2</button>
			<button id="button2" class="btn btn-success" onclick="product()">multiply num1 and num2</button>
			<button id="button3" class="btn btn-success" onclick="difference()">subtract num1 and num2</button>
			<button id="button4" class="btn btn-success" onclick="compare()">Is num1 = num2</button>
		</form>
	</center>
	<script type="text/javascript">
		function add(){
			var num1 = document.getElementById("input1").value; //assign value for num1
			var num2 = document.getElementById("input2").value; //assign value for num2
			var sum = Number(num1) + Number(num2); //formula for sum
			window.alert("The sum of num1 and num2 : " + sum)
		}
		function product(){
			var num1 = document.getElementById("input1").value; //assign value for num1
			var num2 = document.getElementById("input2").value; //assign value for num2
			var product = Number(num1) * Number(num2); //formula for product
			window.alert("The product of num1 and num2 : " + product)
		}
		function difference(){
			var num1 = document.getElementById("input1").value; //assign value for num1
			var num2 = document.getElementById("input2").value; //assign value for num2
			var difference = Number(num1) - Number(num2); //formula for difference
			window.alert("The difference of num1 and num2 : " + difference)
		}
		function compare(){
			var num1 = document.getElementById("input1").value; //assign value for num1
			var num2 = document.getElementById("input2").value; //assign value for num2
			var compare = Number(num1) == Number(num2); //formula for product
			window.alert("Is num1 equal to num2 : " + compare)
		}


	</script>
</body>
</html>
