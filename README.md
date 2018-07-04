<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="../docs/comingSoon.css">
	<title>Spoiler</title>
</head>
<body>
	<!----------------------------------------------------------------------------------------------------->
	<script type="text/javascript">
	// Set the date we're counting down to
var countDownDate = new Date("Jul 6, 2018 23:59:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get todays date and time
  var now = new Date().getTime();

  // Find the distance between now an the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in an element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);</script>
	<!----------------------------------------------------------------------------------------------------->
	<div class="bgimg">
		<div class="topleft">
			<img src="WhatsApp Image 2018-06-25 at 10.27.58.jpg">
		</div>
		<div class="middle">
			<h1>COMING SOON</h1>
			<hr>
			<p id="demo">35 days</p>
		</div>
		<div class="bottomleft">
			<p>The Game is coming...</p>
		</div>
	</div> 
</body>
</html>
