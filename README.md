Binary
jaycee delosreyes 
/
binary
Public
Code
Issues
Pull requests
Actions
Projects
Security
Insights
binary/index.html
@carlcastanas
carlcastanas Update index.html
 1 contributor
38 lines (35 sloc)  1.46 KB
<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Binary Converter</title>
  <link rel="stylesheet" href="./style.css">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
  <link rel = "icon" href = "https://i.ibb.co/Ryp4bsF/Pics-Art-08-25-03-06-14-removebg-preview.png" type = "image/x-icon">

</head>
<body>

<!-- partial:index.partial.html -->

<div class="container">
	<div class="tools">
		<button class="sub toggle">REVERSE</button>
		<button class="sub clear clear-converted">CLEAR</button>    
		<button class="convert">CONVERT</button>
		<button class="unconvert">UNCONVERT</button>
	</div>
	<div class="decimalToBinary">
		<textarea autofocus class="decimal" placeholder="Text to Binary"></textarea>
		<textarea class="binary disabled" placeholder="Binary"></textarea>
	</div>
	<div class="binaryToDecimal">
		<textarea class="binary" placeholder="Binary to Text"></textarea>
		<textarea class="decimal disabled" placeholder="Text"></textarea>
	</div>
</div>
<!-- partial -->
  <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js'></script><script  src="./script.js"></script>
      <script src="particles.js"></script>
        <script src="app.js"></script>
        <script src='https://cdnjs.cloudflare.com/ajax/libs/gsap/1.20.3/TweenMax.min.js'></script><script  src="./hover.js"></script>
</body>
</html>
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
binary/index.html at master · carlcastanas/binary
