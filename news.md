---
layout: page
permalink: /news/
---

{% include menu.html %}
<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v8.0" nonce="LlOs07kQ"></script>

<div id="demo"></div>
<h1>News</h1>

<!--iframe width="560" height="315" src="https://www.youtube.com/embed/r-batujRAfg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe-->
<h3>Nabami Cultural</h3>
<iframe width="560" height="315" src="https://www.youtube.com/embed/xdk0z5Wu6yU" frameborder="0" allowfullscreen></iframe>
<br/><br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/CcIYjADXk-E" frameborder="0" allowfullscreen></iframe>
<h3>Ashtami Cultural</h3>
<iframe width="560" height="315" src="https://www.youtube.com/embed/wSHeRlya92g" frameborder="0" allowfullscreen></iframe>
<br/><br/>
<h3>Saptami Cultural</h3>
<iframe width="560" height="315" src="https://www.youtube.com/embed/qZKXW7GJY-o" frameborder="0" allowfullscreen></iframe>
<br/><br/>
<h3>Sasthi Cultural</h3>
<iframe width="560" height="315" src="https://www.youtube.com/embed/r-batujRAfg" frameborder="0"  allowfullscreen></iframe>



<!--h2 style="color:orange;">Panchami</h2>
For more Panchami pics <a href="/2019_panchami.html">click here</a>
<img style="margin-left:1px;" src="../images/puja2019/panchami.jpg" alt="image"/><br/-->
<img style="margin-left:1px;" src="../images/puja2020/nirghonto.jpg" alt="image"/><br/>

<h3>Event: Saptami Pushpanjali</h3>
<div class="fb-page" data-href="https://www.facebook.com/Meghamallar-Pujo-2020-105600611335211" data-tabs="timeline" data-width="" data-height="" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="true"><blockquote cite="https://www.facebook.com/Meghamallar-Pujo-2020-105600611335211" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/Meghamallar-Pujo-2020-105600611335211">Meghamallar Pujo 2020</a></blockquote></div>





<script>
/******************/
// Set the date we're counting down to
var countDownDate = new Date("Oct 21, 2020 18:00:00").getTime();

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
