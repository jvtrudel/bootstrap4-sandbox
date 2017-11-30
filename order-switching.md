---
layout: basics
title: Switching content order 
despription: Change div order at breakpoint
---

<main class="container-fluid" style="background-color: #F0F0F0">

<section class="container-fluid" style="background-color: darkgray">
<h3>Horizontal to vertical at sm</h3>

<div class="row">
<div class="col-sm-5 mx-auto">
	<h5> Pane 1</h5>
{{site.data.text.p3}}
</div>
<div class="col-sm-5 mx-auto">
	<h5>Pane framboise</h5>
{{site.data.text.p3}}
</div>
</div>
</section>

<section class="container-fluid" style="background-color: lightgray">
<h3>Left to right at sm</h3>

<div class="row">
<div class="col-5 order-3 order-sm-1 mx-auto">
	<h5> Pane 1</h5>
{{site.data.text.p3}}
</div>
<div class="col-5 order-2 mx-auto">
	<h5>Pane framboise</h5>
{{site.data.text.p3}}
</div>
</div>

</section>

<section class="container-fluid" style="background-color: darkgray">
<h3>Switch both horizontal and vertical order at sm</h3>

<div class="row">
<div class="col-sm-5 order-3 order-sm-1 mx-auto">
	<h5> Pane 1</h5>
{{site.data.text.p3}}
</div>
<div class="col-sm-5 order-2 mx-auto">
	<h5>Pane framboise</h5>
{{site.data.text.p3}}
</div>
</div>
</section>

</main>