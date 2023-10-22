---
layout: page
permalink: /news/
---

{% include menu.html %}
<div id="fb-root"></div>


<div style="color: orange; font-size:1.5em;font-weight: bold;" id="demo"></div>

<br/><br/>
<h2>2023 Astami Updates</h2>

<img style="border:1px solid black;" src="/images/puja2023/2023-astami5.jpg"><img>
Astami Bhog Nibedaner por<br/>


<img style="border:1px solid black;" src="/images/puja2023/2023-astami4.jpg"><img>
<br/>


<img style="border:1px solid black;" src="/images/puja2023/2023-astami3.jpg"><img>
Astami Bhog Nibedan<br/>


<img style="border:1px solid black;" src="/images/puja2023/2023-astami2.jpg"><img>
Astami Pushpanjali - last round<br/>

<img style="border:1px solid black;" src="/images/puja2023/2023-astami1.jpg"><img>
photo credit: Prof. Salil Sanyal<br/>


<br/><br/>
<h2>2023 Saptami Updates</h2>

<img style="border:1px solid black;" src="/images/puja2023/2023-saptami3.jpg"><img>
Saptami Udbodhani Sangeet<br/>

<img style="border:1px solid black;" src="/images/puja2023/2023-saptami2.jpg"><img>
photo credit: Prof. Salil Sanyal<br/>

<img style="border:1px solid black;" src="/images/puja2023/2023-saptami1.jpg"><img>


<br/><br/>

<h2>2023 Sasthi Highlights</h2>
<img style="border:1px solid black;" src="/images/puja2023/ma1.png"><img>
photo credit: Ronnie<br/>

<br/>
<br/>
<img style="border:1px solid black;" src="/images/puja2023/agomoni1.png"><img>
photo credit: Prof. Salil Sanyal<br/>

<script>
		function daysRemaining() {
		  var day  = 19
		  var month = 10
		  var year = 2023

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

