---
id: 290
title: Firefox | problem with ARIA tag in tbody
date: 2014-02-26T23:45:27+00:00
author: Manish
layout: single
guid: https://13.68.136.88/?p=290
permalink: /blog/firefox-problem-with-aria-tag-in-tbody/
dsq_thread_id:
  - "2328702754"
categories:
  - Web Accessibility
tags:
  - accessibility
  - aria
  - html5
---

I recently ran into an issue with firefox not rendering a table correctly for use with a screen reader.  
The table was rendered correctly visually on the screen. However, when using a screen reader, the entire body of the table, i.e. all the rows and columns in the table, appeared as a single line of continuous text to the screen reader and no table navigation commands were possible within the text.  
The same table was exposed correctly to the same screen reader in Internet Explorer though.

It turned out that the HTML table had some aria tags in the tbody tag that were not required. The aria tags were being generated by the javascript that was rendering the table HTML. the ARIA tags were useless and weren't required for the tbody tag.
Firefox, however, tried to interpret the tags and messed up the table for screen readers where, in my opinion, Firefox should have simply ignored the tags if it did not understand them.  
Typical accessibility issues are caused because of a lack of ARIA markup or things like missing alt text, invalid or missing closing tags etc. This was peculiar because this was caused because of extra ARIA tags and not because of a lack of them.  
This issue could not be captured by any accessibility tool out there. Neither would an average developer who is simply aware of the W3C accessibility guidelines and is consciously trying to stick to the standards would have found this out without a screen reader user actually reporting the issue.  

In the end, i wasted a lot of time trying to figure out what was going on here.  
In the next few days, I will collect some resources on ARIA tags and their correct usage and post them here. Hopefully that will help people spot tags that shouldn't be there.