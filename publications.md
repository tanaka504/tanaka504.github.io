---
layout: page
title: Publications
permalink: /publications/
---

<h3 class="member-role"><span>国際会議・WorkShop</span></h3> 

<ol>
{% for entry in site.data.publications.International %}
    <li>
        <div class="title">{{ entry.title }}</div>
        <div class="authors">{{ entry.authors }}</div>
        <div class="info">{{ entry.info }}</div>
    </li>
{% endfor %}
</ol>

<h3 class="member-role"><span>国内会議</span></h3> 

<ol>
{% for entry in site.data.publications.Domestic %}
    <li>
        <div class="title">{{ entry.title }}</div>
        <div class="authors">{{ entry.authors }}</div>
        <div class="info">{{ entry.info }}</div>
    </li>
{% endfor %}
</ol>