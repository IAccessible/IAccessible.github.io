---
id: 65
title: Progressive Enhancement
date: 2014-02-06T05:00:18+00:00
author: Manish
layout: page
guid: 'https://13.68.136.88//?post_type=articles&#038;p=65'
---
<div id="main_content" class="span9">
			<p class="lead">Web site should make basic content available to everyone while more advanced content and functionality will be accessible to those with more capability</p><p>
			
			</p><h3>Browser Incompatibilities</h3>
			<p>Use <a href="http://modernizr.com/">modernizr.js</a> to identify browser support and features. It will help applying <a href="https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-browser-Polyfills">pollyfills</a> to support cross browser support
			</p>
			<pre class="prettyprint prettyprinted" style=""><span class="com">// Give Modernizr.load a string, an object, or an array of strings and objects</span><span class="pln">
</span><span class="typ">Modernizr</span><span class="pun">.</span><span class="pln">load</span><span class="pun">([</span><span class="pln">
  </span><span class="com">// Presentational polyfills</span><span class="pln">
  </span><span class="pun">{</span><span class="pln">
    </span><span class="com">// Logical list of things we would normally need</span><span class="pln">
    test </span><span class="pun">:</span><span class="pln"> </span><span class="typ">Modernizr</span><span class="pun">.</span><span class="pln">fontface </span><span class="pun">&amp;&amp;</span><span class="pln"> </span><span class="typ">Modernizr</span><span class="pun">.</span><span class="pln">canvas </span><span class="pun">&amp;&amp;</span><span class="pln"> </span><span class="typ">Modernizr</span><span class="pun">.</span><span class="pln">cssgradients</span><span class="pun">,</span><span class="pln">
    </span><span class="com">// Modernizr.load loads css and javascript by default</span><span class="pln">
    nope </span><span class="pun">:</span><span class="pln"> </span><span class="pun">[</span><span class="str">'presentational-polyfill.js'</span><span class="pun">,</span><span class="pln"> </span><span class="str">'presentational.css'</span><span class="pun">]</span><span class="pln">
  </span><span class="pun">},</span><span class="pln">
  </span><span class="com">// Functional polyfills</span><span class="pln">
  </span><span class="pun">{</span><span class="pln">
    </span><span class="com">// This just has to be truthy</span><span class="pln">
    test </span><span class="pun">:</span><span class="pln"> </span><span class="typ">Modernizr</span><span class="pun">.</span><span class="pln">websockets </span><span class="pun">&amp;&amp;</span><span class="pln"> window</span><span class="pun">.</span><span class="pln">JSON</span><span class="pun">,</span><span class="pln">
    </span><span class="com">// socket-io.js and json2.js</span><span class="pln">
    nope </span><span class="pun">:</span><span class="pln"> </span><span class="str">'functional-polyfills.js'</span><span class="pun">,</span><span class="pln">
    </span><span class="com">// You can also give arrays of resources to load.</span><span class="pln">
    both </span><span class="pun">:</span><span class="pln"> </span><span class="pun">[</span><span class="pln"> </span><span class="str">'app.js'</span><span class="pun">,</span><span class="pln"> </span><span class="str">'extra.js'</span><span class="pln"> </span><span class="pun">],</span><span class="pln">
    complete </span><span class="pun">:</span><span class="pln"> </span><span class="kwd">function</span><span class="pln"> </span><span class="pun">()</span><span class="pln"> </span><span class="pun">{</span><span class="pln">
      </span><span class="com">// Run this after everything in this group has downloaded</span><span class="pln">
      </span><span class="com">// and executed, as well everything in all previous groups</span><span class="pln">
      myApp</span><span class="pun">.</span><span class="pln">init</span><span class="pun">();</span><span class="pln">
    </span><span class="pun">}</span><span class="pln">
  </span><span class="pun">},</span><span class="pln">
  </span><span class="com">// Run your analytics after you've already kicked off all the rest</span><span class="pln">
  </span><span class="com">// of your app.</span><span class="pln">
  </span><span class="str">'post-analytics.js'</span><span class="pln">
</span><span class="pun">]);</span><span class="pln">
			</span></pre>
			<h3>Internet Explorer Issues</h3>
			<p>Use <a href="http://modernizr.com/">html5shiv</a> to resolve issues related to IE 8 and its earlier version 
			</p>
			<pre class="prettyprint lang-html prettyprinted" style=""><span class="com">&lt;!--[if lt IE 9]&gt;
&lt;script src="dist/html5shiv.js"&gt;&lt;/script&gt;
&lt;![endif]--&gt;</span><span class="pln">
			</span></pre>
        </div>