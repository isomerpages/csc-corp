---
title: Organisation Structure
permalink: /organisation-structure/
description: ""
---
<style>
.hidecontent {
	 display: none;
	
	}
	
	.Label_alignment {
	 padding-left:10px
	
	}
	
#myaccordian label {
	box-shadow:0 0 20px #d4d4d4;
	display: block;
	padding 8px 22px;
	margin: 10px 0px 1px 0px;
	cursor: pointer;
	background: #f7dbbe;
	font-weight: bold ;
	transition: ease .5s;
	
	
	}
	
	#myaccordian label:hover{
		background :#F68B1F;
	  color: white;
	
	}
	
	.accordiancontent {
		/* box-shadow: 0px 0px 20px #d4d4d4; */
		padding: 10px 25px;
	  /* border: 1px solid #d4d4d4; */
	}
	
	#myaccordian input:checked + label + .accordiancontent{
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
	  grid-template-columns:  30% 70%;
	 
	}

	.header-left {
		text-align: left;
	
	
	}

	.Accordian-Paragraph {
	 font-size: 1em;
	
	}
	

</style>
<!-- Hello there this is a HTML comment-->

<p>CSC's five Institutes, three Business Support units and six Corporate Services departments work to help us achieve our mission of preparing public officers for the future. Find out about how we're organised and what we do.                         </p>

<hr>
<div class="grid-container">
<div class="grid-child-OS-1"><h3 style="textalign:left;" class="header-left">Dean's Office</h3></div>
<div class="grid-child-OS-2">
	<ul>
	<li>Ms Ong Toon Hui, Dean and CEO</li>
	<li>Mr Hoe Wee Meng, Assistant CEO (Corporate)</li>
	<li>Mr Patrick Lau, Assistant CEO (Strategy and Transformation)</li>
	<li>Mr Roger Tan, Assistant CEO (International)</li>

</ul>
</div>
</div>


<hr>
<div class="grid-container">
	<div class="grid-child-OS-1"><h3 class="header-left">Institutes</h3>
	</div>
	<div class="grid-child-OS-2">
		<div id="myaccordian">
			<input class="hidecontent" id="accordian1" type="checkbox">
			<label class="Label_alignment" for="accordian1">Institute of Governance and Policy</label>
		<div class="accordiancontent hidecontent">
			<p class="Accordian-Paragraph">Steward and advance public policy through research and training programmes,  with emphasis on the areas of governance, public economics and social policy.</p>
</div>
			<input class="hidecontent" id="accordian2" type="checkbox">
			<label class="Label_alignment" for="accordian2">Institute of Leadership and Organisation Development</label>
		<div class="accordiancontent hidecontent">
			<p class="Accordian-Paragraph">Develop leadership and organisation development (OD) capabilities through research, training and consultancy, so as to enable sustainable change and transformation in the Public Service.</p>
</div>
		<!-- Institute of Leadership and Organisation development accordian is above. Institute of Public Administration and Management accordian is below.-->
			<input class="hidecontent" id="accordian3" type="checkbox">
			<label class="Label_alignment" for="accordian3">Institute of Public Administration and Management</label>
		<div class="accordiancontent hidecontent">
			<p class="Accordian-Paragraph">Build capabilities in the areas of service management and delivery, strategic human resource management, public finance and law, public service foundational competencies and enforcement practices.</p>
</div>
<!-- Above is Institue of Public Administration and Management accordian. Below is the Institute of public sector leadership accordian.-->		
			<input class="hidecontent" id="accordian4" type="checkbox">
			<label class="Label_alignment" for="accordian4">Institute of Public Sector Leadership</label>
		<div class="accordiancontent hidecontent">
			<p class="Accordian-Paragraph">Develop a pipeline of public service leaders through a suite of milestone programmes focusing on leadership development, public governance and its ethos in Singapore.</p>
</div>
		<!-- Above is the Institute of public sectors leadership accordian. Below is the Civil Service College International accordian-->
			<input class="hidecontent" id="accordian5" type="checkbox">
			<label class="Label_alignment" for="accordian5">Civil Service College International</label>
		<div class="accordiancontent hidecontent">
			<p class="Accordian-Paragraph">Build strategic partnerships through the sharing of Singapore’s public service experience and best practices with the wider global community.</p>
</div>
		
 
 </div>
</div>

<hr>
<div class="grid-container">
	<div class="grid-child-OS-1"><h3 class="header-left">Business Support Units</h3>
	</div>
<div class="grid-child-OS-2">
	<!-- Below here will be the 3 Business Support unit accordians-->
	<div id="myaccordian">
			<input class="hidecontent" id="accordian6" type="checkbox">
			<label class="Label_alignment" for="accordian6">Digital Learning Services</label>
		<div class="accordiancontent hidecontent">
			<p class="Accordian-Paragraph">Drive and enable digital learning for an integrated and seamless learning experience.</p>
     </div>
	</div>
	<!-- Above is the Digital Learning Services Accordian. Below is the Learning Futures Group accordian.-->
   <div id="myaccordian">
			<input class="hidecontent" id="accordian7" type="checkbox">
			<label class="Label_alignment" for="accordian7">Learning Futures Group</label>
		<div class="accordiancontent hidecontent">
			<p class="Accordian-Paragraph">Nurture conditions for continual experimentation and innovation in learning design and technology.</p>
     </div>
    </div>
	<!-- Above is the Learning Futures Group accordian. Below is the Programme Management Unit accordian. -->
	<div id="myaccordian">
			<input class="hidecontent" id="accordian8" type="checkbox">
			<label class="Label_alignment" for="accordian8">Programme Management Unit</label>
		<div class="accordiancontent hidecontent">
			<p class="Accordian-Paragraph">Partner institutes to provide end-to-end administrative and logistics support for training programmes and other forms of learning interventions so that learners enjoy a seamless experience in their learning journey.</p>
	  	</div>	
   </div>
	
	

<hr>
<div class="grid-container">
	<div class="grid-child-OS-1">
		<h3>Corporate Services</h3>
  </div>
	<div class="grid-child-OS-2"></div>

</div></div></div></div>