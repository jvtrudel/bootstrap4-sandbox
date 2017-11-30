---
layout: basics
title: Grids demonstration
description: Show how to make grids layout
---

<main class="container-fluid" style="background-color: #F0F0F0">

<section class="container-fluid" style="background-color: darkgray">
<h3>Rows and columns</h3>
<div class="row">
<div class="col-4">
<h5>Pane A</h5>
{{site.data.text.p1}}
</div>
<div class="col-8">
	<h5>Pane Grenadine</h5>
	{{site.data.text.p1}}
</div>
</div>
<div class="row">
<div class="col-7">
<h5>Pane Guadeloupe</h5>
{{site.data.text.p1}}
</div>
<div class="col-5">
	<h5>Pane B</h5>
	{{site.data.text.p1}}
</div>
</div>
</section>



<section class="container-fluid" style="background-color: darkgray">
<h3>Sub Grids</h3>
<div class="row">

<div class="col-4">
<h5>Pane Citrouille</h5>
{{site.data.text.p1}}
</div>
<div class="col-8">
	<h5>Pane Pastiche</h5>
	<div class="row">
	<div class="col-3">
		<h6> ici on a une sous colonne</h6>
		{{site.data.text.p1}}
	</div>
	<div class="col-6">
	<h6> là, on a l'autre!</h6>
	{{site.data.text.p1}}
	</div>
	</div>
</div>


</div>
</section>



</main>