---
layout: page
permalink: /news/
---

{% include menu.html %}
<div id="fb-root"></div>


<div style="color: orange; font-size:1.5em;font-weight: bold;" id="demo"></div>

<br/><br/>

<img style="border:1px solid black;" src="/images/puja2024/puja-nirghonto.png"><img>


<script>
		function daysRemaining() {
		  var day  = 9
		  var month = 10
		  var year = 2024

		  var daystocount=new Date(year, month -1, day)
		  today=new Date()
		  daystocount.setFullYear(daystocount.getFullYear())
		  var oneday=1000*60*60*24
		  var daysToGo = (Math.ceil((daystocount.getTime()-today.getTime())/(oneday)))
		  var text1 = "45th Durgapuja 2023 : just ";

		  if (daysToGo > 1) {
			   text1 += daysToGo + " days to go ...";
			document.getElementById('demo').innerHTML += text1;

		  }
		  else if (daysToGo == 1) {
			   text1 += "1 day to go ...";
			   document.getElementById('demo').innerHTML += text1;

		  }
		  else if (daysToGo > -7) {
			  var count = daysToGo *(-1) + 1;
			  text1 = "<img src='../images/"+count+".jpg'/>";
			   document.getElementById('demo').innerHTML += text1;

		  }
		  else
			  document.getElementById('demo').innerHTML += "<img src='../images/8.jpg'/>";

		}

		daysRemaining();
		document.getElementById("newsbtn").style.backgroundColor = "orange";



</script>

