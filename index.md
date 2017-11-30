---
layout: basics
title: Démonstrations 
---

<ul>
{%for page in site.pages%}
{%if page.url != "/"%}
   <li><a href=".{{page.url}}">{{page.title}}</a></li>
{%endif%}
{%endfor%}
</ul>