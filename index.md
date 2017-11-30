---
layout: basics
title: Démonstrations 
description: A set of minimal examples using Bootstrap 4  
---

<ul>
{%for page in site.pages%}
{%if page.url != "/"%}
   <li><a href=".{{page.url}}">{{page.title}}</a></li>
{%endif%}
{%endfor%}
</ul>

<p>Source code use jekyll and can be found at <a href="https://github.com/jvtrudel/bootstrap4-sandbox" target="_blank">https://github.com/jvtrudel/bootstrap4-sandbox</a>