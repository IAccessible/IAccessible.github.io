---
id: 39
title: Guideline 1.3 Adaptable
date: 2014-02-06T04:47:48+00:00
author: Manish
layout: page
guid: 'https://13.68.136.88//?post_type=articles&#038;p=39'
---
<div class="span9" id="main_content">
	<p class="lead">
		Create content that can be presented in different ways (for example simpler layout) without losing information or structure.
	</p>

	<h4>1.3.1 Information and Relationships conveyed through presentation are programmatically determined or available in text</h4>
	<div class="tabbable" >

		<!-- Only required for left/right tabs -->
		<ul class="nav nav-tabs" role="tablist">
			<li class="active" role="presentation">
				<a id="#tabs1_1" href="#tab1_1" data-toggle="tab" role="tab" aria-controls="tab1_1" aria-selected="true">Inaccessible Stuff</a>
			</li>
			<li role="presentation">
				<a id="#tabs1_2" href="#tab1_2" data-toggle="tab" role="tab" aria-controls="tab1_2" aria-selected="false">How to make it Accessible</a>
			</li>
		</ul>
		<div class="tab-content">
			<div class="tab-pane active" id="tab1_1" role="tabpanel" aria-labelledby="tabs1_1">
				<ul>
					<li>
						<a title="Information Inaccessible Example" href="https://13.68.136.88//information-inaccessible-example/" target="_blank" rel="noopener noreferrer">Information Inaccessible Example</a>
					</li>
				</ul>
			</div>
			<div class="tab-pane" id="tab1_2" role="tabpanel" aria-labelledby="tabs1_2">
				<pre class="prettyprint lang-html prettyprinted"><span class="tag">&lt;strong&gt;</span><span class="pln">special deals</span><span class="tag">&lt;/strong&gt;</span></pre>
			</div>
		</div>
	</div>
	<h4>1.3.2 Sequential Information</h4>
	<div class="tabbable" role="tablist">

		<!-- Only required for left/right tabs -->
		<ul class="nav nav-tabs" role="tablist">
			<li class="active" role="presentation">
				<a id="#tabs2_1" href="#tab2_1" data-toggle="tab" role="tab" aria-controls="tab2_1" aria-selected="true">Inaccessible Stuff</a>
			</li>
			<li role="presentation">
				<a id="#tabs2_2" href="#tab2_2" data-toggle="tab" role="tab" aria-controls="tab2_2" aria-selected="false">How to make it Accessible</a>
			</li>
		</ul>
		<div class="tab-content">
			<div class="tab-pane active" id="tab2_1" role="tabpanel" aria-labelledby="tabs2_1">
				<ul>
					<li>
						<a title="Sequential Information Inaccessible Example" href="https://13.68.136.88//examples/1_3_2" target="_blank" rel="noopener noreferrer">Sequential Information Inaccessible Example</a>
					</li>
				</ul>
			</div>
			<div class="tab-pane" id="tab2_2" role="tabpanel" aria-labelledby="tabs2_2"></div>
		</div>
	</div>
	<h4>1.3.3 Size, Shape and Location are not the only ways that meaning is conveyed</h4>
	<div class="tabbable" role="tablist">

		<!-- Only required for left/right tabs -->
		<ul class="nav nav-tabs" role="tablist">
			<li class="active" role="presentation">
				<a id="#tabs3_1" href="#tab3_1" data-toggle="tab" role="tab" aria-controls="tab3_1" aria-selected="true">Inaccessible Stuff</a>
			</li>
			<li role="presentation">
				<a id="#tabs3_2" href="#tab3_2" data-toggle="tab" role="tab" aria-controls="tab3_2" aria-selected="false">How to make it Accessible</a>
			</li>
		</ul>
		<div class="tab-content">
			<div class="tab-pane active" id="tab3_1" role="tabpanel" aria-labelledby="tabs3_1">
				<ul>
					<li>
						<a title="Location Inaccessible Example" href="https://13.68.136.88//examples/1_3_3" target="_blank" rel="noopener noreferrer">Location Inaccessible Example</a>
					</li>
				</ul>
			</div>
			<div class="tab-pane" id="tab3_2" role="tabpanel" aria-labelledby="tabs3_2">
				<ul>
					<li>
						<a title="Location Accessible Example" href="https://13.68.136.88//examples/1_3_3_success" target="_blank" rel="noopener noreferrer">Location Accessible Example</a>
					</li>
				</ul>
			</div>
		</div>
	</div>
</div>