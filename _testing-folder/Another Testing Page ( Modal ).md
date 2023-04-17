---
title: Another Testing Page ( Modal )
permalink: /testing-folder/testing-page-2/
description: ""
---
<style>

.modal-window {
	opacity: 0;
	z-index:999;
	
	
	}
	
.modal-window:target {
	opacity:1;
	pointer-events: auto;
	}

.modal-window > div {
	width: 80%;
	height: 60%;
	
	
	}



</style>

<a href="#Openmodal">Click me</a>

<div class="modal-window" id="Openmodal">
	<div>
		<a class="modal-close" title="close" href="#modal-close">close x</a>
		<h3>The modal</h3>
	</div>
</div>