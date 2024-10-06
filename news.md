---
layout: page
permalink: /news/
---

{% include menu.html %}
<div id="fb-root"></div>


<div style="color: orange; font-size:1.5em;font-weight: bold;" id="demo"></div>

<br/><br/>
<img style="border:1px solid black;" src="/images/puja2024/ma-panchami.jpg"><img>

পুজো এসে গেল। মা-এর বোধন ৮-ই অক্টোবর, সন্ধ্যা ৬টায়। মেঘমল্লারে সাজো-সাজো রব। পূজাপ্রাঙ্গন , কমিউনিটি হল সরগরম।
<br/><br/>আগামীকাল আনন্দমেলা - অনেক বাড়িতে এখন তার জন্য প্রস্তুতি শুরু হয়ে গেছে।
<br/><br/>
আগামী কয়েকদিন আমাদের এই site আমরা চেষ্টা করব আপনাদের কাছে মেঘমল্লারের পুজোর ছবি ও সংবাদ পৌঁছে দেবার। সঙ্গে থাকবেন !

<img style="border:1px solid black;" src="/images/puja2024/puja-nirghonto.png"><img>
<img style="border:1px solid black;" src="/images/puja2024/2024-sasthi.jpg"><img>
<img style="border:1px solid black;" src="/images/puja2024/2024-saptami.jpg"><img>
<img style="border:1px solid black;" src="/images/puja2024/2024-astami-nabami.jpg"><img>


<script>
		function daysRemaining() {
		  var day  = 8
		  var month = 10
		  var year = 2024

		  var daystocount=new Date(year, month -1, day)
		  today=new Date()
		  daystocount.setFullYear(daystocount.getFullYear())
		  var oneday=1000*60*60*24
		  var daysToGo = (Math.ceil((daystocount.getTime()-today.getTime())/(oneday)))
		  var text1 = "46th Durgapuja 2024 : just ";

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

