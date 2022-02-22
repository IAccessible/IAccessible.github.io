---
id: 53
title: Guideline 3.2 Predictable
date: 2014-02-06T04:51:32+00:00
author: Manish
layout: page
guid: 'https://13.68.136.88//?post_type=articles&#038;p=53'
---
<div id="main_content" class="span9">
	<p class="lead">
		Make Web pages appear and operate in predictable ways.
	</p><p>

	</p><h4>3.2.1 On Focus : When any component receives focus, it does not initiate a change of context. </h4>
	<div class="tabbable">
		<!-- Only required for left/right tabs -->
		<ul class="nav nav-tabs" role="tablist">
			<li class="active" role="presentation">
				<a id="tabs1_1" href="#tab1_1" data-toggle="tab" role="tab" aria-controls="tab1_1" aria-selected="true">Inaccessible stuff</a>
			</li>

		</ul>
		<div class="tab-content">
			<div class="tab-pane active" id="tab1_1" role="tabpanel" aria-labelledby="tabs1_1">

				<p>
					Example Failure 1
				</p>
				<pre class="prettyprint lang-html prettyprinted" style=""><span class="tag">&lt;form</span><span class="pln"> </span><span class="atn">method</span><span class="pun">=</span><span class="atv">"get"</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"form1"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;input</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"text"</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"text1"</span><span class="pln"> </span><span class="atn">size</span><span class="pun">=</span><span class="atv">"3"</span><span class="pln"> </span><span class="atn">maxlength</span><span class="pun">=</span><span class="atv">"3"</span><span class="tag">&gt;</span><span class="pln"> - 
  </span><span class="tag">&lt;input</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"text"</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"text2"</span><span class="pln"> </span><span class="atn">size</span><span class="pun">=</span><span class="atv">"3"</span><span class="pln"> </span><span class="atn">maxlength</span><span class="pun">=</span><span class="atv">"3"</span><span class="tag">&gt;</span><span class="pln"> - 
  </span><span class="tag">&lt;input</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"text"</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"text3"</span><span class="pln"> </span><span class="atn">size</span><span class="pun">=</span><span class="atv">"4"</span><span class="pln"> </span><span class="atn">maxlength</span><span class="pun">=</span><span class="atv">"4"</span><span class="pln"> </span><span class="atn">onchange</span><span class="pun">=</span><span class="atv">"</span><span class="pln">form1</span><span class="pun">.</span><span class="pln">submit</span><span class="pun">();</span><span class="atv">"</span><span class="tag">&gt;</span><span class="pln">
</span><span class="tag">&lt;/form&gt;</span><span class="pln"> 
						</span></pre>				
						

				<p>
					Example Failure 2
				</p>
				<pre class="prettyprint lang-html prettyprinted" style=""><span class="tag">&lt;form</span><span class="pln"> </span><span class="atn">method</span><span class="pun">=</span><span class="atv">"get"</span><span class="pln"> </span><span class="atn">id</span><span class="pun">=</span><span class="atv">"form2"</span><span class="tag">&gt;</span><span class="pln">
 </span><span class="tag">&lt;input</span><span class="pln"> </span><span class="atn">type</span><span class="pun">=</span><span class="atv">"text"</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"text1"</span><span class="tag">&gt;</span><span class="pln">
  </span><span class="tag">&lt;select</span><span class="pln"> </span><span class="atn">name</span><span class="pun">=</span><span class="atv">"select1"</span><span class="pln"> </span><span class="atn">onchange</span><span class="pun">=</span><span class="atv">"</span><span class="pln">form2</span><span class="pun">.</span><span class="pln">submit</span><span class="pun">();</span><span class="atv">"</span><span class="tag">&gt;</span><span class="pln">
    </span><span class="tag">&lt;option&gt;</span><span class="pln">one</span><span class="tag">&lt;/option&gt;</span><span class="pln">
    </span><span class="tag">&lt;option&gt;</span><span class="pln">two</span><span class="tag">&lt;/option&gt;</span><span class="pln">
    </span><span class="tag">&lt;option&gt;</span><span class="pln">three</span><span class="tag">&lt;/option&gt;</span><span class="pln">
    </span><span class="tag">&lt;option&gt;</span><span class="pln">four</span><span class="tag">&lt;/option&gt;</span><span class="pln">
  </span><span class="tag">&lt;/select&gt;</span><span class="pln">
</span><span class="tag">&lt;/form&gt;</span><span class="pln"> 
						</span></pre>
				<p>
					Example Failure 3
				</p>
				<a href="http://www.bjp.org" target="_blank" rel="noopener noreferrer"> BJP </a>
			</div>
		</div>
	</div>

	<h4>3.2.2 Definitions of unusual words, phrases, idioms, jargon and abbreviations are available</h4>
	<div class="tabbable">
		<!-- Only required for left/right tabs -->
		<ul class="nav nav-tabs" role="tablist">
			<li class="active" role="presentation">
				<a id="tabs2_1" href="#tab2_1" data-toggle="tab" role="tab" aria-controls="tab2_1" aria-selected="true">How to make it Accessible</a>
			</li>
		</ul>
		<div class="tab-content">
			<div class="tab-pane active" id="tab2_1" role="tabpanel" aria-labelledby="tabs2_1">
				<ul>
					<li>
						<a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/meaning-idioms.html" target="_blank" rel="noopener noreferrer">WCAG 2.0</a>
					</li>
				</ul>
			</div>
		</div>
	</div>

</div>