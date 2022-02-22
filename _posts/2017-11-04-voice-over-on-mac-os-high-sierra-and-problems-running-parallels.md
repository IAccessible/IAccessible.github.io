---
id: 336
title: Voice over on Mac OS High Sierra and problems running parallels
date: 2017-11-04T04:18:28+00:00
author: Manish
layout: single
guid: https://13.68.136.88/?p=336
permalink: /blog/voice-over-on-mac-os-high-sierra-and-problems-running-parallels/
dsq_thread_id:
  - "6261759452"
categories:
  - IOS
  - mobile accessibility
---
I have set up my mac book pro to run windows virtual machines using parallels. After a lot of hit and trial, I was able to get the following working on earlier versions of the mac OS:
1. Mapped the caps lock key as the voice over key in addition to ctrl+option to avoid voice over commands with too many keys and also to avoid having to move the left hand down for many voice over key combinations.
2. used siel to remap the caps lock keycode to to f14. This did not have any impact on 1 above.
3. In the windows virtual VM, used sharp keys to remap f14 to insert.
  With the above 3 changes, I had an almost normal voice over and NVDA and jaws usability except for the fact that I lost the regular caps lock in both windows and Mac - something that did bother me but only sometimes.

I recently upgraded to Mac OS high sierra and the above setup broke.
1. Siel no longer works in high sierra and I have to instead use Karabiner Elements. Karabiner elements allows remapping the caps lock key directly to insert, thus allowing me to avoid mapping the key first to f14 and then using sharp keys in windows to map f14 to insert.
2. After this remapping with karabiner elements, windows is back to the earlier state. However, the voice over key can no longer be mapped to caps lock. 
3. I couldn't find any option to set the voice over key to "insert" either.
4. I still don't have a regular caps lock in either windows or Mac now.

The loss of caps lock as the voice over key may sound like a small thing but is extremely significant for my productivity not to mention anyone with motor difficulties who cannot use too many keys together.