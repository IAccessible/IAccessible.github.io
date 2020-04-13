---
id: 301
title: Accurev client for windows accessibility
date: 2014-09-15T03:02:01+00:00
author: Manish
layout: single
guid: https://13.68.136.88/?p=301
permalink: /blog/accurev-client-for-windows-accessibility/
dsq_thread_id:
  - "3018830523"
categories:
  - Windows accessibility
tags:
  - accessibility
  - accurev
  - jab
  - java
---
If you are in the unfortunate situation of having to use accurev as your source control system and are wondering how to get a screen reader to make any sense of the UI, read on.  
   The installer for the accurev client uses java and I haven't found a way of making that accessible. My only solution was to get sighted help to install the client.  
    The accurev client uses its own JRE that gets installed in the same folder as accurev. So, even if you have the Java access bridge installed on your system, the screen reader will not be able to read anything in accurev.  
        You need to install another copy of the java access bridge in the accurev-specific JRE folder. The instructions for installing the java access bridge can be found at the [Oracle java access bridge documentation page](http://docs.oracle.com/javase/accessbridge/2.0.2/setup.htm).  Remember to put all the JRE folder specific files in the accurev JRE folder and not in the folder where java is installed by default on your system.  
        Once you do this, you will need to restart the accurev client, if it was already running.  
        
The screen reader, NVDA or jaws, must be launched before the accurev client is launched. Otherwise, the screen reader is not able to plug into the accessibility events raised by the accurev-specific JRE.  
On similar lines, if you need to restart the screen reader for some reason while the accurev client is already running, you will need to restart the accurev client as well.  
    Finally, the current jaws version 15.* doesn't really work well with accurev even after doing all of the above and has a tendency to simply hang. 
    NVDA is fairly stable and does provide access to almost all parts of the accurev client application through a combination of keyboard and object navigation. 
    There are some things that are not usable even with NVDA. The key among these being diff and merge. For these, I have configured a tool called "beyond compare" in accurev. beyond compare is launched any time you try to do a diff or merge in the accurev client and is almost completely accessible with both jaws and NVDA.