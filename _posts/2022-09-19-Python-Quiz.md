---
keywords: fastai
description: Python Quiz
title: Python Quiz
toc: true
badges: true
comments: true
categories: [Posts]
nb_path: _notebooks/2022-09-19-Python-Quiz.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-19-Python-Quiz.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Welcome to my Python Quiz!</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">quiz</span><span class="p">():</span>
    <span class="n">points</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="n">questions</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Who won the 2021-2022 Premier League Title?&quot;</span><span class="p">,</span> <span class="s2">&quot;Which Premier League team has won the most titles?&quot;</span><span class="p">,</span> <span class="s2">&quot;Who is the all time leading scorer in the Premier League?&quot;</span><span class="p">,</span> <span class="s2">&quot;Who is the most successful Premier League Manager?&quot;</span><span class="p">,</span> <span class="s2">&quot;How many teams play in the Premier League?&quot;</span><span class="p">,</span> <span class="s2">&quot;How Many teams are relegated every year?&quot;</span><span class="p">,</span> <span class="s2">&quot;When was the Premier League officially Founded?&quot;</span><span class="p">]</span>
    <span class="n">answers</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;Manchester City&quot;</span><span class="p">,</span> <span class="s2">&quot;Manchester United&quot;</span><span class="p">,</span> <span class="s2">&quot;Alan Shearer&quot;</span><span class="p">,</span> <span class="s2">&quot;Sir Alex Ferguson&quot;</span><span class="p">,</span> <span class="s2">&quot;20&quot;</span><span class="p">,</span> <span class="s2">&quot;3&quot;</span><span class="p">,</span> <span class="s2">&quot;1992&quot;</span><span class="p">]</span>
    <span class="n">num</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="k">while</span> <span class="n">num</span> <span class="o">&lt;=</span> <span class="mi">6</span><span class="p">:</span>
        <span class="n">answer</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="n">questions</span><span class="p">[</span><span class="n">num</span><span class="p">])</span>
        <span class="k">if</span> <span class="n">answer</span> <span class="o">==</span> <span class="n">answers</span><span class="p">[</span><span class="n">num</span><span class="p">]:</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Correct&quot;</span><span class="p">)</span>
            <span class="n">points</span> <span class="o">=</span> <span class="n">points</span> <span class="o">+</span> <span class="mi">1</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Incorrect&quot;</span><span class="p">)</span>
        <span class="n">num</span> <span class="o">+=</span> <span class="mi">1</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You got:&quot;</span><span class="p">,</span> <span class="p">(</span><span class="n">points</span><span class="o">/</span><span class="mi">7</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">,</span> <span class="s2">&quot;%&quot;</span><span class="p">)</span>
<span class="n">quiz</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Correct
Correct
Correct
Correct
Correct
Correct
Correct
Correct
You got: 100.0 %
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 
