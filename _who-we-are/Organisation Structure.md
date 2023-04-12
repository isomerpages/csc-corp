---
title: Organisation Structure
permalink: /organisation-structure/
description: ""
---
<style>
.hidecontent {
	 display: none;
	
	}
#myaccordian label {
	box-shadow:0 0 20px #d4d4d4;
	display: block;
	padding 8px 22px;
	margin: 20px 0px 1px 0px;
	cursor: pointer;
	background: #5f75a4;
	color: #FFF
	transition: ease .5s;
	
	
	}
	
	#myaccordian label:hover{
		background: #5f75ff
	
	}
	
	.accordiancontent {
		box-shadow: 0px 0px 20px #d4d4d4;
	  background: #ffff;
		padding: 10px 25px;
	  border: 1px solid #d4d4d4;
	}
	
	#myaccordian input:checked + label + .content{
	  display: block;
	  web-kit animation: fadeIn 0.5s ease-out;
		-moz-animation: fadeIn 0.5s ease-out;
	  -o-animation: fadeIn 0.5s ease-out;
		animation: fadeIn 0.5s ease-out;
	
	
	}
	
	@-webkit-keyframes fadeIn {
		0%{
		display: none;
		opacity: 0;
	}
	1%{
		display: block;
		opacity: 0;
	}
	100%{
		display:block;
		opacity: 0;
	}
	}
	
.grid-container {
	  display: grid;
	  grid-template-columns: 1fr 1fr;
	 
	}

	.header-left {
		text-align: left;
	
	
	}

	.Accordian-Paragraph {
	 font-size: 1em;
	
	}
	

</style>


<p>CSC's five Institutes, three Business Support units and six Corporate Services departments work to help us achieve our mission of preparing public officers for the future. Find out about how we're organised and what we do.                         </p>

<hr>
<div class="grid-container">
<div class="grid-child-OS"><h2 style="text-align:left;" class="header-left">Dean's Office</h2></div>
<div class="grid-child-OS">
	<ul>
	<li>Ms Ong Toon Hui, Dean and CEO</li>
	<li>Mr Hoe Wee Meng, Assistant CEO (Corporate)</li>
	<li>Mr Patrick Lau, Assistant CEO ( Strategy and Transformation )</li>
	<li>Mr Roger Tan, Assistant CEO ( International ) Institutes</li>

</ul>
</div>
</div>


<hr>
<div class="grid-container">
	<div class="grid-child-OS"><h2 class="header-left">Institutes</h2></div>
	<div class="grid-child-OS">
		<details>
			<summary><h5>Institute of Governance and Policy</h5>
			</summary>
			<p class="Accordian-Paragraph">Steward and advance public policy through research and training programmes,  with emphasis on the areas of governance, public economics and social policy.
			</p>
			
</details>
		<div id="myaccordian">
			<input class="hidecontent" id="accordian1" type="checkbox">
		<label for="accordian1">Hello there Tester1234</label>
		<div class="accordiancontent hidecontent">
			<p>Hello there </p>
</div>
	</div>
	
	
 
 </div>
</div>

<hr>
<div class="grid-container">
	<div class="grid-child-OS"><h2 class="header-left">Business Support Units</h2></div>
	<div class="grid-child-OS"></div>


</div>

<hr>