# Code Sample

Example FizzBuzz program written by me

### HTML
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i < 101; i++) {
		if(i % 3 == 0 && i % 5 == 0){
			document.write("FizzBuzz", "<br>")
		}
		else if (i % 3 == 0){
        document.write("Fizz", "<br>");
    	}
   		else if (i % 5 == 0){
        document.write("Buzz", "<br>");
    	}
    	else{
        document.write(i, "<br>");
		}
		displayHTML += "<p>" + i + "</p>";

	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```

[return to home page](./README.md)