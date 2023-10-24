---
layout: page
permalink: /news/
---

{% include menu.html %}
<div id="fb-root"></div>


<div style="color: orange; font-size:1.5em;font-weight: bold;" id="demo"></div>

<I>Photo Credit for all updates - Prof. Salil Sanyal</I>


<h2>2023 Dasami shokal - Updates</h2>

<img style="border:1px solid black;" src="/images/puja2023/da1.jpg"><img>
Dasami Puja<br/>

<img style="border:1px solid black;" src="/images/puja2023/da2.jpg"><img>
Maa Durga r Kochur Shak<br/>


<br/><br/>
<I>Photo Credit & captions for all updates - Prof. Salil Sanyal</I>
<h2>2023 Nabami shokal - Updates</h2>

<img style="border:1px solid black;" src="/images/puja2023/n1.jpg"><img>
<br/>

<img style="border:1px solid black;" src="/images/puja2023/n2.jpg"><img>
<br/>

<img style="border:1px solid black;" src="/images/puja2023/n3.jpg"><img>
<br/>

<img style="border:1px solid black;" src="/images/puja2023/n4.jpg"><img>
<br/>

<img style="border:1px solid black;" src="/images/puja2023/n5.jpg"><img>
<br/>

<img style="border:1px solid black;" src="/images/puja2023/n6.jpg"><img>
<br/>

<img style="border:1px solid black;" src="/images/puja2023/n7.jpg"><img>
<br/>

<img style="border:1px solid black;" src="/images/puja2023/n8.jpg"><img>
Shastange Pronam<br/>


<br/><br/>
<h2>2023 Astami Sandhi Pujo - Updates</h2>

<img style="border:1px solid black;" src="/images/puja2023/s1.jpg"><img>
Sandhi Pujor torjor<br/>

<img style="border:1px solid black;" src="/images/puja2023/s2.jpg"><img>
Sandhi Pujo shuru<br/>

<img style="border:1px solid black;" src="/images/puja2023/s3.jpg"><img>
Sandhi Pujor Bhog Nibedan<br/>

<img style="border:1px solid black;" src="/images/puja2023/s4.jpg"><img>
Sandhi Pujor Anjali<br/>

<img style="border:1px solid black;" src="/images/puja2023/s5.jpg"><img>
Sandhi Pujor Arati<br/>

<img style="border:1px solid black;" src="/images/puja2023/s6.jpg"><img>
Sandhi Pujor Alo jwalano<br/>

<img style="border:1px solid black;" src="/images/puja2023/s7.jpg"><img>
Sandhi Pujor Alo jwalano<br/>


<br/><br/>
<h2>2023 Astami Shokal - Updates</h2>

<img style="border:1px solid black;" src="/images/puja2023/2023-astami5.jpg"><img>
Astami Bhog Nibedaner por<br/>


<img style="border:1px solid black;" src="/images/puja2023/2023-astami4.jpg"><img>
<br/>


<img style="border:1px solid black;" src="/images/puja2023/2023-astami3.jpg"><img>
Astami Bhog Nibedan<br/>


<img style="border:1px solid black;" src="/images/puja2023/2023-astami2.jpg"><img>
Astami Pushpanjali - last round<br/>

<img style="border:1px solid black;" src="/images/puja2023/2023-astami1.jpg"><img>


<br/><br/>
<h2>2023 Saptami Updates</h2>

<img style="border:1px solid black;" src="/images/puja2023/2023-saptami3.jpg"><img>
Saptami Udbodhani Sangeet<br/>

<img style="border:1px solid black;" src="/images/puja2023/2023-saptami2.jpg"><img>

<img style="border:1px solid black;" src="/images/puja2023/2023-saptami1.jpg"><img>


<br/><br/>

<h2>2023 Sasthi Highlights</h2>
<img style="border:1px solid black;" src="/images/puja2023/ma1.png"><img>
photo credit: Ronnie<br/>

<br/>
<br/>
<img style="border:1px solid black;" src="/images/puja2023/agomoni1.png"><img>

<img style="border:1px solid black;" src="/images/puja2023/sasthi0.jpg"><img>
Beltala where Bodhan takes place


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

