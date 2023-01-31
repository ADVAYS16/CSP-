---
keywords: fastai
description: HTML and Javascript Fragments
title: HTML and Javascript Fragments
toc: true
badges: true
comments: true
categories: [Posts]
nb_path: _notebooks/2022-10-17-HTML-Table.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-10-17-HTML-Table.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>I will demonstrate usage of both HTML fragments and Javascript to make a table of the top 5 goal scorers in Champion's League History.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><script>
    var statistics = [
        {id: 1, name: "Cristiano Ronaldo", Goals: 140, Appearances: 183, Age: 37},
        {id: 2, name: "Lionel Messi", Goals: 127, Appearances: 159, Age: 35},
        {id: 3, name: "Robert Lewandowski", Goals: 91, Appearances: 110, Age: 34},
        {id: 4, name: "Karim Benzema", Goals: 86, Appearances: 145, Age: 34},
        {id: 5, name: "Raul", Goals: 71, Appearances: 142, Age: 45}
]
</script></p>
<table class="table table-hover table-dark table-striped">
<tr>
    <th>Rank</th>
    <th>Name</th>
    <th>Goals</th>
    <th>Appearances</th>
    <th>Age</th>
</tr>
<script>
    var output = "";
    for (index in statistics) {
        output += '<tr><td>';
        output += statistics[index].id;
        output += '</td>';
        output += '<td>';
        output += statistics[index].name;
        output += '</td>';
        output += '<td>';
        output += statistics[index].Goals;
        output += '</td>';
        output += '<td>';
        output += statistics[index].Appearances;
        output += '</td>';
        output += '<td>';
        output += statistics[index].Age;
        output += '</td>';
        output += '</tr>';
    }
    document.write(output);
</script>
</table>
</div>
</div>
</div>
</div>
 
