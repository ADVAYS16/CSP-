---
keywords: fastai
description: Python Hacks
title: Python Hacks "Week 2"
toc: true
badges: true
comments: true
categories: [Posts]
nb_path: _notebooks/2022-09-22-Python-Hacks.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-22-Python-Hacks.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">InfoDb</span> <span class="o">=</span> <span class="p">[]</span>

<span class="c1"># InfoDB is a data structure with expected Keys and Values</span>

<span class="c1"># Append to List a Dictionary of key/values related to a person and cars</span>
<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;John&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Mortensen&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;October 21&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;jmortensen@powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;2015-Fusion&quot;</span><span class="p">,</span> <span class="s2">&quot;2011-Ranger&quot;</span><span class="p">,</span> <span class="s2">&quot;2003-Excursion&quot;</span><span class="p">,</span> <span class="s2">&quot;1997-F350&quot;</span><span class="p">,</span> <span class="s2">&quot;1969-Cadillac&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="c1"># Append to List a 2nd Dictionary of key/values</span>
<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Sunny&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Naidu&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;August 2&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;Temecula&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;snaidu@powayusd.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;4Runner&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="n">InfoDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;FirstName&quot;</span><span class="p">:</span> <span class="s2">&quot;Advay&quot;</span><span class="p">,</span>
    <span class="s2">&quot;LastName&quot;</span><span class="p">:</span> <span class="s2">&quot;Shindikar&quot;</span><span class="p">,</span>
    <span class="s2">&quot;DOB&quot;</span><span class="p">:</span> <span class="s2">&quot;December 16&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Residence&quot;</span><span class="p">:</span> <span class="s2">&quot;San Diego&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Email&quot;</span><span class="p">:</span> <span class="s2">&quot;advay1216@gmail.com&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Owns_Cars&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;Porsche 911&quot;</span><span class="p">]</span>
<span class="p">})</span>

<span class="c1"># Print the data structure</span>
<span class="nb">print</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">)</span>
<span class="n">x</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[{&#39;FirstName&#39;: &#39;John&#39;, &#39;LastName&#39;: &#39;Mortensen&#39;, &#39;DOB&#39;: &#39;October 21&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;Email&#39;: &#39;jmortensen@powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;2015-Fusion&#39;, &#39;2011-Ranger&#39;, &#39;2003-Excursion&#39;, &#39;1997-F350&#39;, &#39;1969-Cadillac&#39;]}, {&#39;FirstName&#39;: &#39;Sunny&#39;, &#39;LastName&#39;: &#39;Naidu&#39;, &#39;DOB&#39;: &#39;August 2&#39;, &#39;Residence&#39;: &#39;Temecula&#39;, &#39;Email&#39;: &#39;snaidu@powayusd.com&#39;, &#39;Owns_Cars&#39;: [&#39;4Runner&#39;]}, {&#39;FirstName&#39;: &#39;Advay&#39;, &#39;LastName&#39;: &#39;Shindikar&#39;, &#39;DOB&#39;: &#39;December 16&#39;, &#39;Residence&#39;: &#39;San Diego&#39;, &#39;Email&#39;: &#39;advay1216@gmail.com&#39;, &#39;Owns_Cars&#39;: [&#39;Porsche 911&#39;]}]
3
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">InfoDb</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
<span class="n">i</span> <span class="o">=</span> <span class="mi">0</span>
<span class="k">def</span> <span class="nf">print_data</span><span class="p">(</span><span class="n">d_rec</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;FirstName&quot;</span><span class="p">],</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;LastName&quot;</span><span class="p">])</span>  <span class="c1"># using comma puts space between values</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Residence:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Residence&quot;</span><span class="p">])</span> <span class="c1"># \t is a tab indent</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Birth Day:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;DOB&quot;</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;Cars: &quot;</span><span class="p">,</span> <span class="n">end</span><span class="o">=</span><span class="s2">&quot;&quot;</span><span class="p">)</span>  <span class="c1"># end=&quot;&quot; make sure no return occurs</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;, &quot;</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Owns_Cars&quot;</span><span class="p">]))</span>  <span class="c1"># join allows printing a string list with separator</span>
    <span class="nb">print</span><span class="p">()</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span> <span class="p">(</span><span class="n">x</span><span class="p">):</span>
    <span class="n">record</span> <span class="o">=</span> <span class="n">InfoDb</span><span class="p">[</span><span class="n">i</span><span class="p">]</span>
    <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>
    <span class="n">i</span> <span class="o">+=</span> <span class="mi">1</span> 
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>3
John Mortensen
	 Residence: San Diego
	 Birth Day: October 21
	 Cars: 2015-Fusion, 2011-Ranger, 2003-Excursion, 1997-F350, 1969-Cadillac

Sunny Naidu
	 Residence: Temecula
	 Birth Day: August 2
	 Cars: 4Runner

Advay Shindikar
	 Residence: San Diego
	 Birth Day: December 16
	 Cars: Porsche 911

</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">QuizDb</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">QuizDb</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;Q1&quot;</span><span class="p">:</span> <span class="s2">&quot;Who won the 2021-2022 Premier League Title?&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A1&quot;</span><span class="p">:</span> <span class="s2">&quot;Manchester City&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Q2&quot;</span><span class="p">:</span> <span class="s2">&quot;Which Premier League team has won the most titles?&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A2&quot;</span><span class="p">:</span> <span class="s2">&quot;Manchester United&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Q3&quot;</span><span class="p">:</span> <span class="s2">&quot;Who is the all time leading scorer in the Premier League?&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A3&quot;</span><span class="p">:</span> <span class="s2">&quot;Alan Shearer&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Q4&quot;</span><span class="p">:</span> <span class="s2">&quot;Who is the most successful Premier League Manager?&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A4&quot;</span><span class="p">:</span> <span class="s2">&quot;Sir Alex Ferguson&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Q5&quot;</span><span class="p">:</span> <span class="s2">&quot;How many teams play in the Premier League?&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A5&quot;</span><span class="p">:</span> <span class="s2">&quot;20&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Q6&quot;</span><span class="p">:</span> <span class="s2">&quot;How many teams are relegated each year?&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A6&quot;</span><span class="p">:</span> <span class="s2">&quot;3&quot;</span><span class="p">,</span>
    <span class="s2">&quot;Q7&quot;</span><span class="p">:</span> <span class="s2">&quot;When was the premier league officially founded?&quot;</span><span class="p">,</span>
    <span class="s2">&quot;A7&quot;</span><span class="p">:</span> <span class="s2">&quot;1992&quot;</span>
   
<span class="p">})</span>

<span class="k">def</span> <span class="nf">quiz</span><span class="p">():</span>
    <span class="n">f</span> <span class="o">=</span> <span class="mi">1</span>
    <span class="n">score</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="k">while</span> <span class="n">f</span> <span class="o">&lt;=</span> <span class="mi">7</span><span class="p">:</span>
        <span class="n">answer</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="n">QuizDb</span> <span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s2">&quot;Q&quot;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">f</span><span class="p">)])</span>
        <span class="k">if</span> <span class="n">answer</span> <span class="o">==</span> <span class="n">QuizDb</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s2">&quot;A&quot;</span><span class="o">+</span><span class="nb">str</span><span class="p">(</span><span class="n">f</span><span class="p">)]:</span>
            <span class="nb">print</span> <span class="p">(</span><span class="s2">&quot;correct&quot;</span><span class="p">)</span>
            <span class="n">score</span> <span class="o">+=</span> <span class="mi">1</span>
        <span class="k">else</span><span class="p">:</span> 
            <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;incorrect&quot;</span><span class="p">)</span>
        <span class="n">f</span> <span class="o">+=</span><span class="mi">1</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;You Recieved&quot;</span><span class="p">,</span> <span class="mi">100</span><span class="o">*</span><span class="p">(</span><span class="n">score</span><span class="o">/</span><span class="mi">7</span><span class="p">),</span> <span class="s2">&quot;%&quot;</span><span class="p">)</span>
<span class="n">quiz</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>correct
You Recieved 14.285714285714285 %
correct
You Recieved 28.57142857142857 %
correct
You Recieved 42.857142857142854 %
correct
You Recieved 57.14285714285714 %
correct
You Recieved 71.42857142857143 %
correct
You Recieved 85.71428571428571 %
correct
You Recieved 100.0 %
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

