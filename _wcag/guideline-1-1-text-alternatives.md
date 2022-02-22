---
id: 37
title: Guideline 1.1 Text Alternatives
date: 2014-02-06T04:46:27+00:00
author: Manish
layout: page
guid: 'https://13.68.136.88//?post_type=articles&#038;p=37'
---
<div class="span9" id="main_content">
	<p class="lead">
		Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language
	</p>
	<h3>1.1.1 Links - alt text in img tag</h3>
	<div class="tabbable">

		<!-- Only required for left/right tabs -->
		<ul class="nav nav-tabs" role="tablist">
			<li class="active" role="presentation">
				<a id="tabs1_1"href="#tab1_1" data-toggle="tab" role="tab" aria-controls="tab1_1" aria-selected="true">Inaccessible Stuff</a>
			</li>
			<li role="presentation">
				<a id="tabs1_2" href="#tab1_2" data-toggle="tab" role="tab" aria-controls="tab1_2" aria-selected="false">How to make it Accessible</a>
			</li>
		</ul>
		<div class="tab-content">
			<div class="tab-pane active" id="tab1_1" role="tabpanel" aria-labelledby="tabs1_1">
				<ul>
					<ul>
						<li>
							No alt text at all - <a href="http://www.licindia.in/" target="_blank" rel="noopener noreferrer">LIC India</a>
						</li>
						<li>
							Irrelevant alt text : Look at alt text under "CONTACT US" image - <a href="http://www.licindia.in/" target="_blank" rel="noopener noreferrer">LIC India</a>
						</li>
						<li>
							Alt text for image when it is not required - spacer, horizontal and vertical line images etc.
						</li>
					</ul>
				</ul>
				<a title="Example Page" href="http://localhost/iaccessible//example-page/">Alt not required Example </a>
				<ul>
					<li>
						Using CSS for image display : Look at footer for payment options - <a href="http://www.snapdeal.com/" target="_blank" rel="noopener noreferrer">Snapdeal</a>
					</li>
				</ul>
			</div>
			<div class="tab-pane" id="tab1_2" role="tabpanel" aria-labelledby="tabs1_2">

				Look at weather information at http://bbc.com or any other image
				<pre class="prettyprint lang-html prettyprinted"><span class="tag">&lt;img</span><span class="atn">alt</span><span class="pun">=</span><span class="atv">"Sunny"</span><span class="atn">title</span><span class="pun">=</span><span class="atv">"Sunny"</span><span class="atn">src</span><span class="pun">=</span><span class="atv">"url"</span><span class="atn">class</span><span class="pun">=</span><span class="atv">"icon"</span><span class="tag">&gt;</span></pre>
				Spacer are used properly at <a href="http://www.licindia.in/" target="_blank" rel="noopener noreferrer">LIC India</a>
				<pre class="prettyprint lang-html prettyprinted"><span class="tag">&lt;img</span><span class="atn">src</span><span class="pun">=</span><span class="atv">"pages/spacer.gif"</span><span class="atn">width</span><span class="pun">=</span><span class="atv">"36"</span><span class="atn">height</span><span class="pun">=</span><span class="atv">"1"</span><span class="atn">alt</span><span class="pun">=</span><span class="atv">""</span><span class="tag">&gt;</span></pre>
			</div>
		</div>
	</div>
	<h3>1.1.2 Labeling of controls</h3>
	<div class="tabbable">

		<!-- Only required for left/right tabs -->
		<ul class="nav nav-tabs" role="tablist">
			<li class="active" role="presentation">
				<a id="tabs2_1" href="#tab2_1" data-toggle="tab" role="tab" aria-controls="tab2_1" aria-selected="true">Inaccessible Stuff</a>
			</li>
			<li role="presentation">
				<a id="tabs2_2" href="#tab2_2" data-toggle="tab" role="tab" aria-controls="tab2_2" aria-selected="false">How to make it Accessible</a>
			</li>
		</ul>
		<div class="tab-content">
			<div class="tab-pane active" id="tab2_1" role="tabpanel" aria-labelledby="tabs2_1">
				<ul>
					<li>
						<a title="Inaccessible / Accessible Controls Example" href="http://localhost/iaccessible//examples/1_1_2" target="_blank" rel="noopener noreferrer"> Inaccessible / Accessible Controls Example </a>
					</li>
				</ul>
			</div>
			<div class="tab-pane" id="tab2_2" role="tabpanel" aria-labelledby="tabs2_2">
				<pre class="prettyprint lang-html prettyprinted"><span class="tag">&lt;label</span><span class="atn">for</span><span class="pun">=</span><span class="atv">"mr"</span><span class="tag">&gt;</span><span class="pln">Mr. </span><span class="tag">&lt;input</span><span class="atn">type</span><span class="pun">=</span><span class="atv">"radio"</span><span class="atn">name</span><span class="pun">=</span><span class="atv">"t"</span><span class="atn">id</span><span class="pun">=</span><span class="atv">"mr"</span><span class="atn">value</span><span class="pun">=</span><span class="atv">"mr"</span><span class="atn">title</span><span class="pun">=</span><span class="atv">"title"</span><span class="tag">&gt;&lt;/label&gt;</span></pre>
			</div>
		</div>
	</div>
	<h3>1.1.3 CAPTCHA</h3>
	<div class="tabbable">

		<!-- Only required for left/right tabs -->
		<ul class="nav nav-tabs" role="tablist">
			<li class="active" role="presentation">
				<a id="tabs3_1" href="#tab3_1" data-toggle="tab" role="tab" aria-controls="tab3_1" aria-selected="true">Inaccessible Stuff</a>
			</li>
			<li role="presentation">
				<a id="tabs3_2" href="#tab3_2" data-toggle="tab" role="tab" aria-controls="tab3_2" aria-selected="false">How to make it Accessible</a>
			</li>
		</ul>
		<div class="tab-content">
			<div class="tab-pane active" id="tab3_1" role="tabpanel" aria-labelledby="tabs3_1">
				<ul>
					<li>
						<a href="https://www.irctc.co.in/" target="_blank" rel="noopener noreferrer"> Indian Railways Website </a>
					</li>
				</ul>
			</div>
			<div class="tab-pane" id="tab3_2" role="tabpanel" aria-labelledby="tabs3_2">
				<ul>
					<li>
						Math Puzzle
						<ul>
							<li>
								What is 2 + 4 = ?
							</li>
						</ul>
					</li>
					<li>
						Trivia Puzzle
						<ul>
							<li>
								What is the color of sky?
							</li>
						</ul>
					</li>
					<li>
						SMS Verification
						<ul>
							<li>
								Send an SMS for verification similar to Google or Facebook
							</li>
						</ul>
					</li>
				</ul>
			</div>
		</div>
	</div>
</div>