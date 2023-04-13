---
title: Current Test
permalink: /testing-folder/permalink/
description: ""
---
<style>
.hidecontent {
	 display: none;
	
	}
	
	.Label\_alignment {
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
		/\* box-shadow: 0px 0px 20px #d4d4d4; \*/
		padding: 10px 25px;
	  /\* border: 1px solid #d4d4d4; \*/
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
<h2>This is a testing page.</h2>
<hr>

<details>
	<summary>Here is the testing accordian.</summary>
	<p>Here is the content</p>


</details>

<div id="myaccordion">
  <input type="checkbox" id="accordion1" class="hidecontent">
  <label for="accordion1" class="Label_alignment">Communications and Customer Engagement</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Steward corporate identity and customer intelligence, as well as communication and customer engagement with public agencies and public officers.</p>
  </div>

  <input type="checkbox" id="accordion2" class="hidecontent">
  <label for="accordion2" class="Label_alignment">Corporate Development</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Manage finance and procurement functions, estate and administrative matters, and resource centre.</p>
  </div>

  <input type="checkbox" id="accordion3" class="hidecontent">
  <label for="accordion3" class="Label_alignment">Data Office</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Strengthen data infrastructure and expedite the growth of data capabilities.</p>
  </div>

  <input type="checkbox" id="accordion4" class="hidecontent">
  <label for="accordion4" class="Label_alignment">Human Resources</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Nurture engaged and committed staff, develop professional competencies, promote best HR practices, and maintain sound corporate governance.</p>
  </div>

  <input type="checkbox" id="accordion5" class="hidecontent">
  <label for="accordion5" class="Label_alignment">Infocomm Technology</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Develop technical infrastructure and harness digital technology to boost business efficiency and deliver good customer experience.</p>
  </div>

  <input type="checkbox" id="accordion6" class="hidecontent">
  <label for="accordion6" class="Label_alignment">Strategy and Transformation Office</label>
  <div class="accordioncontent hidecontent">
    <p class="Accordion-Paragraph">Develop transformation strategy and roadmap, monitor progress of key projects and ensure alignment of College's resources, including strategy, data, and business model.</p>
  </div>
</div>


