---
id: 59
title: HTML4 and WAI-ARIA
date: 2014-02-06T04:55:58+00:00
author: Manish
layout: page
guid: 'https://13.68.136.88//?post_type=articles&#038;p=59'
---
<div class="span9" id="main_content">
<p class="lead">It make Rich Internet applications more accessible to people with disabilities. It especially helps with dynamic content and advanced user interface controls developed with Ajax, HTML, JavaScript, and related technologies.</p>

<h3>No Semantic Meaning</h3>
Using DIV tags : <a href="http://airtel.in/" target="_blank" rel="noopener noreferrer">Airtel</a>.

Using HTML tables <a href="http://www.rcom.co.in/Rcom/personal/home/index.html" target="_blank" rel="noopener noreferrer">Reliance Communication</a>. <strong>Never user HTML tables for layout</strong>
<h3>Example markup</h3>
<pre class="prettyprint lang-html prettyprinted"><span class="dec">&lt;!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"&gt;</span><span class="tag">&lt;html</span><span class="atn">xmlns</span><span class="pun">=</span><span class="atv">"http://www.w3.org/1999/xhtml"</span><span class="tag">&gt;</span><span class="tag">&lt;head&gt;</span><span class="tag">&lt;title&gt;</span><span class="pln">Demo Layout</span><span class="tag">&lt;/title&gt;</span><span class="tag">&lt;link</span><span class="atn">href</span><span class="pun">=</span><span class="atv">"css/some.css"</span><span class="atn">rel</span><span class="pun">=</span><span class="atv">"stylesheet"</span><span class="tag">&gt;</span><span class="tag">&lt;script</span><span class="atn">src</span><span class="pun">=</span><span class="atv">"js/some.js"</span><span class="atn">type</span><span class="pun">=</span><span class="atv">"text/javascript"</span><span class="tag">&gt;&lt;/script&gt;</span><span class="tag">&lt;head&gt;</span><span class="tag">&lt;body&gt;</span><span class="tag">&lt;div</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"header"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;div</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"navigation"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;div</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"main"</span><span class="tag">&gt;</span><span class="tag">&lt;div</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"side-navigation"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;div</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"content"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;div</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"footer"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;/body&gt;</span><span class="tag">&lt;/html&gt;</span></pre>
<h3>Custom Java Script Component</h3>
Inaccessible Custom Component : <a href="http://nickperkinslondon.github.io/angular-bootstrap-nav-tree/test/bs2_ng120_test_page.html" target="_blank" rel="noopener noreferrer">Tree Widget</a>.
<h3>AJAX</h3>
Dynamic HTML with server side interaction. Autocomplete Example : <a href="https://www.irctc.co.in/" target="_blank" rel="noopener noreferrer">IRCTC</a>.
<h3>Example Markup with ARIA</h3>
<pre class="prettyprint lang-html prettyprinted"><span class="dec">&lt;!DOCTYPE html &gt;</span><span class="tag">&lt;html&gt;</span><span class="tag">&lt;head&gt;</span><span class="tag">&lt;title&gt;</span><span class="pln">Demo Layout</span><span class="tag">&lt;/title&gt;</span><span class="tag">&lt;link</span><span class="atn">href</span><span class="pun">=</span><span class="atv">"css/some.css"</span><span class="atn">rel</span><span class="pun">=</span><span class="atv">"stylesheet"</span><span class="tag">&gt;</span><span class="tag">&lt;script</span><span class="atn">src</span><span class="pun">=</span><span class="atv">"js/some.js"</span><span class="atn">type</span><span class="pun">=</span><span class="atv">"text/javascript"</span><span class="tag">&gt;&lt;/script&gt;</span><span class="tag">&lt;head&gt;</span><span class="tag">&lt;body&gt;</span><span class="tag">&lt;div</span><span class="atn">role</span><span class="pun">=</span><span class="atv">"banner"</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"header"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;div</span><span class="atn">role</span><span class="pun">=</span><span class="atv">"navigation"</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"navigation"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;div</span><span class="atn">role</span><span class="pun">=</span><span class="atv">"main"</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"main"</span><span class="tag">&gt;</span><span class="tag">&lt;div</span><span class="atn">role</span><span class="pun">=</span><span class="atv">"complementary"</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"side-navigation"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;div</span><span class="atn">role</span><span class="pun">=</span><span class="atv">"region"</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"content"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;div</span><span class="atn">role</span><span class="pun">=</span><span class="atv">"contentinfo"</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"footer"</span><span class="tag">&gt;</span><span class="com">&lt;!-- some html code --&gt;</span><span class="tag">&lt;/div&gt;</span><span class="tag">&lt;/body&gt;</span><span class="tag">&lt;/html&gt;</span></pre>
<h3>Java Script Component ARIA</h3>
<h5>Slider</h5>
Slider role, state and attributes <a title="Slider Control" href="https://13.68.136.88//examples/slider-control" target="_blank" rel="noopener noreferrer">Demo In IE</a>
<ul>
	<li><strong>Role</strong> - Slider</li>
	<li><strong>State</strong> - Enable or Disable</li>
	<li><strong>Properties</strong> - Maximum, Minimum and Current level of volume</li>
</ul>
<h5>Tree</h5>
Tree role, state and attributes <a title="Accessible jQuery-ui Components Demonstration" href="https://13.68.136.88//examples/accessible-jqueryui" target="_blank" rel="noopener noreferrer">Demo In IE</a>
<ul>
	<li><strong>Role</strong> - Tree</li>
	<li><strong>State</strong> - Hidden</li>
	<li><strong>Properties</strong> - Multi selectable etc</li>
</ul>
</div>