---
title: Accessible Java Script Components
date: 2014-02-06T04:57:17+00:00
author: Manish
layout: single
guid: 'https://13.68.136.88//?post_type=articles&#038;p=63'
---
<div class="span9" id="main_content">
<p class="lead">Technical Solutions to Advance Java Script Components</p>

<h3>ARIA Component from scratch - Tristate check box</h3>
Html code <a title="Demo in IE" href="https://13.68.136.88//examples/tristate" target="_blank" rel="noopener noreferrer">Demo in IE</a>
<pre class="prettyprint lang-html prettyprinted"><span class="tag">&lt;h2&gt;</span><span class="pln">Working Example</span><span class="tag">&lt;/h2&gt;</span><span class="tag">&lt;div</span><span class="atn">id</span><span class="pun">=</span><span class="atv">"example"</span><span class="tag">&gt;</span><span class="tag">&lt;label</span><span class="atn">for</span><span class="pun">=</span><span class="atv">"checkTest"</span><span class="atn">id</span><span class="pun">=</span><span class="atv">"test"</span><span class="tag">&gt;</span><span class="pln">choose a state</span><span class="tag">&lt;/label&gt;</span><span class="tag">&lt;input</span><span class="atn">type</span><span class="pun">=</span><span class="atv">"image"</span><span class="atn">src</span><span class="pun">=</span><span class="atv">"unchecked.gif"</span><span class="atn">alt</span><span class="pun">=</span><span class="atv">"choose a state"</span><span class="atn">id</span><span class="pun">=</span><span class="atv">"checkTest"</span><span class="tag">&gt;</span><span class="tag">&lt;/div&gt;</span></pre>
Java Script code
<pre class="prettyprint prettyprinted"><span class="pln">window</span><span class="pun">.</span><span class="pln">onload </span><span class="pun">=</span><span class="pln"> init</span><span class="pun">;</span><span class="kwd">function</span><span class="pln"> init</span><span class="pun">()</span><span class="pun">{</span><span class="kwd">var</span><span class="pln"> objCheck</span><span class="pun">=</span><span class="pln">document</span><span class="pun">.</span><span class="pln">getElementById</span><span class="pun">(</span><span class="str">'checkTest'</span><span class="pun">);</span><span class="pln">
	objCheck</span><span class="pun">.</span><span class="pln">setAttribute</span><span class="pun">(</span><span class="str">'role'</span><span class="pun">,</span><span class="str">'checkbox'</span><span class="pun">);</span><span class="pln">
	objCheck</span><span class="pun">.</span><span class="pln">setAttribute</span><span class="pun">(</span><span class="str">'aria-checked'</span><span class="pun">,</span><span class="str">'false'</span><span class="pun">);</span><span class="pln">
	objCheck</span><span class="pun">.</span><span class="pln">onclick </span><span class="pun">=</span><span class="kwd">function</span><span class="pun">()</span><span class="pun">{</span><span class="kwd">return</span><span class="pln"> doCheck</span><span class="pun">(</span><span class="pln">objCheck</span><span class="pun">);</span><span class="pun">};</span><span class="pun">}</span><span class="kwd">function</span><span class="pln"> doCheck</span><span class="pun">(</span><span class="pln">objCheck</span><span class="pun">)</span><span class="pun">{</span><span class="kwd">var</span><span class="pln"> currentvalue </span><span class="pun">=</span><span class="pln"> objCheck</span><span class="pun">.</span><span class="pln">getAttribute</span><span class="pun">(</span><span class="str">'aria-checked'</span><span class="pun">);</span><span class="kwd">switch</span><span class="pun">(</span><span class="pln">currentvalue</span><span class="pun">)</span><span class="pun">{</span><span class="kwd">case</span><span class="str">'false'</span><span class="pun">:</span><span class="pln">
		objCheck</span><span class="pun">.</span><span class="pln">setAttribute</span><span class="pun">(</span><span class="str">'src'</span><span class="pun">,</span><span class="str">'mixed.gif'</span><span class="pun">);</span><span class="pln">
		objCheck</span><span class="pun">.</span><span class="pln">setAttribute</span><span class="pun">(</span><span class="str">'aria-checked'</span><span class="pun">,</span><span class="str">'mixed'</span><span class="pun">);</span><span class="kwd">break</span><span class="pun">;</span><span class="kwd">case</span><span class="str">'mixed'</span><span class="pun">:</span><span class="pln">
		objCheck</span><span class="pun">.</span><span class="pln">setAttribute</span><span class="pun">(</span><span class="str">'src'</span><span class="pun">,</span><span class="str">'checked.gif'</span><span class="pun">);</span><span class="pln">
		objCheck</span><span class="pun">.</span><span class="pln">setAttribute</span><span class="pun">(</span><span class="str">'aria-checked'</span><span class="pun">,</span><span class="str">'true'</span><span class="pun">);</span><span class="kwd">break</span><span class="pun">;</span><span class="kwd">case</span><span class="str">'true'</span><span class="pun">:</span><span class="pln">
		objCheck</span><span class="pun">.</span><span class="pln">setAttribute</span><span class="pun">(</span><span class="str">'src'</span><span class="pun">,</span><span class="str">'unchecked.gif'</span><span class="pun">);</span><span class="pln">
		objCheck</span><span class="pun">.</span><span class="pln">setAttribute</span><span class="pun">(</span><span class="str">'aria-checked'</span><span class="pun">,</span><span class="str">'false'</span><span class="pun">);</span><span class="pun">}</span><span class="kwd">return</span><span class="kwd">true</span><span class="pun">;</span><span class="pun">}</span></pre>
<h3>Another Example</h3>
ARAI friendly Slider <a title="Demo" href="https://13.68.136.88//examples/slider" target="_blank" rel="noopener noreferrer">Demo</a>.
<ul>
	<li>Look at the more advanced demo <a href="http://files.paciellogroup.com/blogmisc/samples/aria/slider/" target="_blank" rel="noopener noreferrer">here</a>, and description about it <a href="http://blog.paciellogroup.com/2008/06/aria-slider-part-2/" target="_blank" rel="noopener noreferrer">here</a></li>
	<li>Advanced demo <a href="http://files.paciellogroup.com/blogmisc/samples/aria/slider/doubleslider.html" target="_blank" rel="noopener noreferrer">here</a>, and description about it <a href="http://blog.paciellogroup.com/2008/06/aria-slider-part-3/" target="_blank" rel="noopener noreferrer">here</a></li>
</ul>
</div>