# Logical-Question-4

<html>
<head>
<title> Utopian Tree </title>
 <script >
    function getHeight(){
      var n = document.utopian.cycles.value;
      var currentHeight = 1;
         for( i = 1; i <= n; i++){
				if(currentHeight%2 !== 0){
					currentHeight*=2
				}
				else{
					currentHeight+= 1;
					}
								}
				return currentHeight; 
				}
</script>
</head>
<body style=text-align:center;>
<form name="utopian" onsubmit="return getHeight()">
		enter the cycle no : <input type="number" name="cycles"> <br> <br>
		<input type="submit" value="enter">
</form>
<p id="tree"> </p>  
</body>
</html>
