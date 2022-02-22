---
id: 339
title: 'Google communication apps &#8211; design problems'
date: 2017-11-13T16:21:02+00:00
author: Manish
layout: single
guid: https://13.68.136.88/?p=339
permalink: /blog/google-communication-apps-design-problems/
dsq_thread_id:
  - "6281457091"
categories:
  - Uncategorized
tags:
  - accessibility
  - Allo
  - Duo
  - google
  - google voice
  - Hangouts
  - IOS
  - UI Design
---
Google has 4 apps on IOS - maybe more - for communication that I have come across: google voice, allo, Duo, and hangouts.
The product people at google probably have valid reasons for creating 4 different apps for mostly the same thing but what is not understandable is why each of these have a completely different take on one thing they definitely have in common.
The way these apps let you access contacts and/or dial a number is different in all of them.
Google voice is probably the worst in its interface for the dial pad and contacts - at least when seen from the eyes of a screen reader.
in google voice, the dial pad tab shows a standard phone keypad. However, if you usually use touch typing in voice over and need to get a + sign, as is required for all international calls, you first need to move to standard typing and then use the double tab and hold gesture on the 0 key. Something that isn't as simple as it sounds because the change from touch typing to standard typing can only be done when focus is already in the dial pad. This means that you have to first enter one wrong digit, change the typing mode, delete the wrong digit, and then double tab and hold the 0 key to get a plus. Can you count the number of steps needed above?
Not to mention I cannot swipe to the delete button, I have to touch around to find it and then lifting my finger deletes.

This is only a part of the story though. To the right of the dial pad - as seen by a screen reader again -- is the list of contacts from the phone. You can get focus on this list by touching the extreme right edge of the screen and in no other way.
This list is also non standard in many ways but assuming you figure that out and find the person you want to call. double tab here and nothing happens. A few seconds and several double taps later, nothing continues to happen!
It turns out, first you need to change the dial pad to a keyboard by pressing a button next to delete, which is also not in the swipe list. Once you do this, then double tapping the contact will make a call. This used to just call earlier but now pops up the US number google voice will internally call to connect my international call. This last one is because of some change in the IOS platform and not google's fault, I think.
BTW, in the contact list, if you cannot find someone you know is in your phone's contacts, make sure that the edit box that shows the number you are dialing is empty because that acts as a search filter as well for this list.

It is baffling why google will go to all the pains of building all this out and not use the platforms contacts and dial pad options since that is what the user of this platform is most likely to be familiar with.
The other 3 apps, Allo, Duo, and hangouts all have a slightly different way of either getting to the dial pad and contacts or displaying them. I guess Google believes no one user will use more than one of these apps or something like that. Otherwise, will it not be more cost effective to build one way of doing this and reuse across your 4 apps, even if you discount user discomfort?
