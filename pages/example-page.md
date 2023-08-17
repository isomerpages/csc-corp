---
title: Example Page
permalink: /example-page/
---
<style>

	.grid-container {
		display: grid; 
		grid-template-columns: 50% 50%;
		grid-column-gap: 15px;
		margin-bottom: 5%;
	}
	
	
	.header-fellows-middle {
		text-align:center;
		margin-top: 2em !important;
	
	}

	.grid-container {
		display: grid; 
		grid-template-columns: 50% 50%;
		grid-column-gap: 15px;
		margin-bottom: 5%;
	}
	
	.fellow-card {
	
	box-shadow: 0px 4px 4px 0px grey;
	margin-top: 40px;
	position:relative;	
	height: 100%;
	box-sizing: border-box;
	padding: 10px;
	
	
	
	}
	
	.fellowship-card-text {
		
		margin-left: 1em;
		margin-right: 1em;
	}
	
	.fellow-summary {
		font-size:0.9em;
	  line-height: 1.6;
		margin-bottom: 1em;
	}
	
	.card-link {
		border-top: 1px solid grey;
		width:30%;
	  position: absolute;
		bottom: 0;
		margin-bottom: 1em;
		margin-left: 1em;
	 
	
	}
	
	
	
.fellow-duration{
		font-size:0.8em;
		color:grey;
	
	}

.fellowship-image {
	width: 80px !important;
	height: 80px !important; 
	border-radius: 50%;
	float: left;
	margin-left: 1em !important;
	}
	
.fellow-name {
	font-size: 1.25em;
	color: #9F2943;
	}
	
	.fellowship-text {
		display: flex;
		flex-direction: column;
	}
	
	.fellowship-image-div{
		float: left;
	
	
	}
	

/*Below is the mobile query*/	

@media only screen and (max-width: 600px) {
	.grid-container {
		display: block;
	}
	.card-link {
		position: static;
	}
}		
	
</style>


<!-- Start of Fellow Card -->
<div class="fellow-card">
<!-- Below is the HTML that is contained inside the card.-->		
<div class="fellowship-text">
	<div class="fellowship-image-div">
		<!-- Start of Fellowcard Image -->
	<img class="fellowship-image" src="[Insert Fellow Image]">
		<!-- End of Fellowcard Image-->
	</div>
			<div class="fellowship-card-text">
				<!-- Start of Fellow Name-->
				<p class="fellow-name">[Insert Fellow Name]</p>
				<!-- End of Fellow Name-->
			</div>
				<div class="fellowship-card-text">
					<!-- Start of Fellow Duration-->
					<p class="fellow-duration">[Insert Fellow Duration]</p>
					<!-- End of Fellow Duration-->
				</div>
					<div class="fellowship-card-text">
						<!-- Start of Fellow Summary -->
						<div class="fellow-summary">[Insert Fellow Summary]
						</div>
						<!-- End of Fellow Summary -->
					</div>
	<div class="fellowship-card-text card-link">
			<a href="[Insert Fellow Biography]">Read Bio</a>
	</div>
</div>
<!-- End of Fellow Card --></div>