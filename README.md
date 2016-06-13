# TouchDiv
use js make touch div

## How to use
```HTML
<!DOCTYPE html>
<html>
	<head>
		<meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no, width=device-width" />
		<meta charset="UTF-8">
		<style>
		* {
			margin: 0;
			padding: 0;
		}
		#touchDiv {
			height:400px; 
			
			white-space: nowrap;
			background-color:#AAA;
			font-size: 50px; 
			-webkit-user-select:none;
			-moz-user-select:none;
			-o-user-select:none;
			user-select:none;
		}

		</style>
	</head>
	<body>
		
		
		<div id="touchDiv">
			page 2<br>page 2<br>page 3<br>page 4<br>page 5<br>page 6<br>page 7<br>page 8<br>page 9<br>page 10<br>page 11<br>page 12<br>page 13<br>page 14<br>page 15<br>page 16<br>page 17<br>page 18<br>page 18<br>page 18<br>page 18<br>page 18<br>page 18<br>page 18<br>
		</div>
		<div id="show">
		</div>
		
		
		<script src="src/touchDiv.js"></script>
		<script>
			touchDiv(document.getElementById("touchDiv"), {
				topToTopFunc: function() {
					console.log(1);
				},
				buttomToButtomFunc: function() {
					console.log(2);
				}
			});
		</script>
		
</body>
</html>

