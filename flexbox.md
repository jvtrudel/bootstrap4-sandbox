---
layout: basics
title: Flexbox
---
<section class="container-fluid" style="background-color: #F0F0F0">
<h2>Flex rows</h2>
<h3>Normal</h3>
<div class="d-flex flex-row" style="height: 100px; background-color: darkgray;">
  <div class="p-2">Flex item 1</div>
  <div class="p-2">Flex item 2</div>
  <div class="p-2">Flex item 3</div>
</div>
<h3>Reversed order</h3> 
<div class="d-flex flex-row-reverse" style="height: 100px; background-color: lightgray;">
  <div class="p-2">Flex item 1</div>
  <div class="p-2">Flex item 2</div>
  <div class="p-2">Flex item 3</div>
</div>

<h3>Justified content end</h3>
<div class="d-flex flex-row justify-content-end" style="height: 100px; background-color: darkgray;">
  <div class="p-2 ">Flex item 1</div>
  <div class="p-2">Flex item 2</div>
  <div class="p-2">Flex item 3</div>
</div>

<h3>justified content center</h3>
<div class="d-flex justify-content-center" style="height: 100px; background-color: lightgray;">
  <div class="p-2 d-flex">Flex item 1</div>
  <div class="p-2">Flex item 2</div>
  <div class="p-2">Flex item 3</div>
</div>

<h3>aligned item center</h3>
<div class="d-flex align-items-center " style="height: 100px; background-color: darkgray;">
  <div class="p-2 ">Flex item 1</div>
  <div class="p-2">Flex item 2</div>
  <div class="p-2">Flex item 3</div>
</div>

</section>

<section class="container-fluid">
<h2>Order</h2>
<h3>Switch order at md breakpoint</h3>
<div class="d-flex justify-content-around" style="background-color: lightgray;">
  <div class="p-2 order-last order-md-first" >Case A</div>
  <div class="p-2 order-first order-md-last" >Case banane</div>
</div>
</section>
