---
layout: page
permalink: /news/
---

{% include menu.html %}
<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v8.0" nonce="LlOs07kQ"></script>

<div style="border:1px solid black;background:#00008B; color:white;" id="demo"></div>
<h1>News</h1>

<img style="border:1px solid black;" src="/images/puja2021/nirghonto-2021.JPG"><img>






<script>
/******************/
// Set the date we're counting down to
var countDownDate = new Date("Oct 11, 2021 18:00:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

    // Get todays date and time
    var now = new Date().getTime();
    
    // Find the distance between now and the count down dategit status
    var distance = countDownDate - now;
    
    // Time calculations for days, hours, minutes and seconds
    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
    // Output the result in an element with id="demo"
    document.getElementById("demo").innerHTML = "Time remaining for Debi Bodhan : " +  days + "days " + hours + "hrs "
    + minutes + "min " + seconds + "sec ";
    
    // If the count down is over, write some text 
    if (distance < 0) {
        clearInterval(x);
        document.getElementById("demo").innerHTML = "";
    }
}, 1000);
/***************/
</script>
