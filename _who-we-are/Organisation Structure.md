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
	
#myaccordion label {
	
	display: block;
	padding:5px;
	margin: 10px 0px 1px 0px;
	cursor: pointer;
	background: #f7dbbe;
	font-weight: bold ;
	transition: ease .5s;
	min-height:35px;
	border: 1px solid #9F2943;
	box-shadow: 0 0 10px #d4d4d4
	
	}
	
	#myaccordion label:hover{
		background :#F68B1F;
	  color: white;
	
	}
	
	.accordioncontent {
		/* box-shadow: 0px 0px 20px #d4d4d4; */
		padding: 10px 25px;
	  /* border: 1px solid #d4d4d4; */
	}
	
	#myaccordion input:checked + label + .accordioncontent{
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

	.Accordion-Paragraph {
	 font-size: 1em;
	
	}
	
	<!-- After this is the new accordian CSS.-->
	summary:hover{
	cursor: pointer;
	color: white;
	background-color: #F68B1F;
	}
	
summary {
	background-color: #f7dbbe;
	padding:8px;
	margin-bottom: -20px;
  border: 1px solid #9F2943;
	}
	
details[open] {
		background-color: #f7f0f0;
		border-bottom: 1px solid #9F2943;
		border-left: 1px solid #9F2943;
		border-right: 1px solid #9F2943;
	}
	

details {
	box-shadow: 0px 0px 20px #d4d4d4;
	}

</style>
<!-- Hello there this is a HTML comment-->

<p>CSC's five Institutes, three Business Support units and six Corporate Services departments work to help us achieve our mission of preparing public officers for the future. Find out about how we're organised and what we do.                         </p>

<hr>
<div class="grid-container">
<div class="grid-child-OS-1"><h3 class="header-left">Dean’s Office</h3></div>
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
		<details>
			<summary>Institute of Governance and Policy.</summary>
			<p class="Accordion-Paragraph">Steward and advance public policy through research and training programmes,  with emphasis on the areas of governance, public economics and social policy.</p>
		</details>
		
		<div id="myaccordion">
			<input class="hidecontent" id="accordion1" type="checkbox">
			<label class="Label_alignment" for="accordion1">Institute of Governance and Policy</label>
		<div class="accordioncontent hidecontent">
			<p class="Accordion-Paragraph">Steward and advance public policy through research and training programmes,  with emphasis on the areas of governance, public economics and social policy.</p>
</div>
			<input class="hidecontent" id="accordion2" type="checkbox">
			<label class="Label_alignment" for="accordion2">Institute of Leadership and Organisation Development</label>
		<div class="accordioncontent hidecontent">
			<p class="Accordion-Paragraph">Develop leadership and organisation development (OD) capabilities through research, training and consultancy, so as to enable sustainable change and transformation in the Public Service.</p>
</div>
		<!-- Institute of Leadership and Organisation development accordian is above. Institute of Public Administration and Management accordian is below.-->
			<input class="hidecontent" id="accordion3" type="checkbox">
			<label class="Label_alignment" for="accordion3">Institute of Public Administration and Management</label>
		<div class="accordioncontent hidecontent">
			<p class="Accordion-Paragraph">Build capabilities in the areas of service management and delivery, strategic human resource management, public finance and law, public service foundational competencies and enforcement practices.</p>
</div>
<!-- Above is Institue of Public Administration and Management accordian. Below is the Institute of public sector leadership accordian.-->		
			<input class="hidecontent" id="accordion4" type="checkbox">
			<label class="Label_alignment" for="accordion4">Institute of Public Sector Leadership</label>
		<div class="accordioncontent hidecontent">
			<p class="Accordion-Paragraph">Develop a pipeline of public service leaders through a suite of milestone programmes focusing on leadership development, public governance and its ethos in Singapore.</p>
</div>
		<!-- Above is the Institute of public sectors leadership accordian. Below is the Civil Service College International accordian-->
			<input class="hidecontent" id="accordion5" type="checkbox">
			<label class="Label_alignment" for="accordion5">Civil Service College International</label>
		<div class="accordioncontent hidecontent">
			<p class="Accordion-Paragraph">Build strategic partnerships through the sharing of Singapore’s public service experience and best practices with the wider global community.</p>
</div>
		
 
 </div>
</div>
</div>
<hr>
<div class="grid-container">
	<div class="grid-child-OS-1">
		<h3 class="header-left">Business Support Units</h3>
	 </div>
<div class="grid-child-OS-2">
	<!-- Below here will be the 3 Business Support unit accordians-->
	<div id="myaccordion">
			<input class="hidecontent" id="accordion6" type="checkbox">
			<label class="Label_alignment" for="accordion6">Digital Learning Services</label>
		<div class="accordioncontent hidecontent">
			<p class="Accordion-Paragraph">Drive and enable digital learning for an integrated and seamless learning experience.</p>
     </div>
	<!-- Above is the Digital Learning Services Accordian. Below is the Learning Futures Group accordian.-->
	<input class="hidecontent" id="accordion7" type="checkbox">
	<label class="Label_alignment" for="accordion7">Learning Futures Group</label>
		<div class="accordioncontent hidecontent">
			<p class="Accordion-Paragraph">Nurture conditions for continual experimentation and innovation in learning design and technology.</p>
     </div>
	<!-- Above is the Learning Futures Group accordian. Below is the Programme Management Unit accordian. -->
			<input class="hidecontent" id="accordion8" type="checkbox">
			<label class="Label_alignment" for="accordion8">Programme Management Unit</label>
		<div class="accordioncontent hidecontent">
			<p class="Accordion-Paragraph">Partner institutes to provide end-to-end administrative and logistics support for training programmes and other forms of learning interventions so that learners enjoy a seamless experience in their learning journey.</p>
	  	</div>	
   </div>
	</div>
</div>
	

<hr>
<div class="grid-container">
	<div class="grid-child-OS-1">
		<h3>Corporate Services</h3>
  </div>
	  <div class="grid-child-OS-2">
	<div id="myaccordion">
  <input type="checkbox" id="accordion9" class="hidecontent">
  <label for="accordion9" class="Label_alignment">Communications and Customer Engagement</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Steward corporate identity and customer intelligence, as well as communication and customer engagement with public agencies and public officers.</p>
  </div>

  <input type="checkbox" id="accordion10" class="hidecontent">
  <label for="accordion10" class="Label_alignment">Corporate Development</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Manage finance and procurement functions, estate and administrative matters, and resource centre.</p>
  </div>

  <input type="checkbox" id="accordion11" class="hidecontent">
  <label for="accordion11" class="Label_alignment">Data Office</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Strengthen data infrastructure and expedite the growth of data capabilities.</p>
  </div>

  <input type="checkbox" id="accordion12" class="hidecontent">
  <label for="accordion12" class="Label_alignment">Human Resources</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Nurture engaged and committed staff, develop professional competencies, promote best HR practices, and maintain sound corporate governance.</p>
  </div>

  <input type="checkbox" id="accordion13" class="hidecontent">
  <label for="accordion13" class="Label_alignment">Infocomm Technology</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Develop technical infrastructure and harness digital technology to boost business efficiency and deliver good customer experience.</p>
  </div>

  <input type="checkbox" id="accordion14" class="hidecontent">
  <label for="accordion14" class="Label_alignment">Strategy and Transformation Office</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Develop transformation strategy and roadmap, monitor progress of key projects and ensure alignment of College's resources, including strategy, data, and business model.</p>
  </div>
</div>






















	
	
	
	
		
		
		
		
</div><!-- This div tag is for the grid-child-os-2-->

</div><!-- This div tag is for the grid-container corporate services.-->