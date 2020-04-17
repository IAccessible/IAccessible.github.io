---
id: 57
title: Guideline 4.1 Compatible
date: 2014-02-06T04:54:30+00:00
author: Manish
layout: page
guid: 'https://13.68.136.88//?post_type=articles&#038;p=57'
---
<div class="span9" id="main_content">
<p class="lead">Maximize compatibility with current and future user agents, including assistive technologies.</p>

<h3>Testing Tools</h3>
<h4>XHTML Validation</h4>
Firefox addon XHTML testing <a href="https://addons.mozilla.org/en-US/firefox/addon/html-validator/" target="_blank" rel="noopener noreferrer">HTML Validator</a>

Example : Visually Good but <a title="Companion Training" href="https://13.68.136.88//companion-training/" target="_blank" rel="noopener noreferrer">Inaccessible Web page</a>
<h4>WAVE Toolbar</h4>
Firefox addon accessibility testing <a href="http://wave.webaim.org/toolbar/" target="_blank" rel="noopener noreferrer">WAVE Toolbar</a>
<h4>Colour Contrast Analyser</h4>
Online <a href="http://snook.ca/technical/colour_contrast/colour.html" target="_blank" rel="noopener noreferrer">Colour Contrast Check</a>
<h4>Manual Testing</h4>
There is no alternative to manual testing.
<ul>
	<li>Testing tools cannot tell context of element. Any wrong alt text can easily pass automation testing.</li>
	<li>Error identification - color changes cannot be determined by automation</li>
	<li>Use keyboard as input device to catch keyboard traps, focus issues, fly out menus issues. Try it - <a href="http://www.bjp.org/">BJP Website</a></li>
	<li>Turn off the images - In IE Go to Internet Options &gt; Advanced &gt; Multimedia &gt; Show pictures OFF</li>
	<li>Take feedback from disabled user</li>
	<li>Use screen reader like NVDA to test. Use "speech viewer" - Tools &gt; Speech Viewer</li>
</ul>
</div>