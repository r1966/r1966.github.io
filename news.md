---
layout: page
permalink: /news/
---

{% include menu.html %}
<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v8.0" nonce="LlOs07kQ"></script>

<div style="color:white;" id="demo"></div>
<h1>News - Pujo 2022</h1>
<h2>Panchami Highlights : Anandamela</h2>
<img style="border:1px solid black;" src="/images/puja2022/2022-anandamela.jpg"><img>
photo credit: Shanu

<h2>Chaturthi Highlights : Naru Preparations</h2>
<img style="border:1px solid black;" src="/images/puja2022/2022-preparations1.jpg"><img>
photo credit: Rajashree
<br/><br/>
<h2>Puja Nirghonto</h2>
<img style="border:1px solid black;" src="/images/puja2022/nirghonto-2022.jpg"><img>




<script>
		function daysRemaining() {
		  var day  = 30
		  var month = 9
		  var year = 2022

		  var daystocount=new Date(year, month -1, day)
		  today=new Date()
		  daystocount.setFullYear(daystocount.getFullYear())
		  var oneday=1000*60*60*24
		  var daysToGo = (Math.ceil((daystocount.getTime()-today.getTime())/(oneday)))
		  var count = daysToGo *(-1) + 1;

		  if (daysToGo > -7) {
			  var text1 = "<img src='../images/"+count+".jpg'/>";
			  document.getElementById('demo').innerHTML += text1;
		  }
		  else {
			  var text2 = "<img src='../images/"+count+".jpg'/>";
			  document.getElementById('demo').innerHTML += text2;
		  }

		}

		daysRemaining();
		document.getElementById("newsbtn").style.backgroundColor = "orange";



</script>

