---
id: 123
title: Information Inaccessible Example
date: 2014-02-12T07:12:12+00:00
author: Manish
layout: page
guid: https://13.68.136.88//?page_id=123
page_location:
  - 'No'
---

 <h1>Failure</h1>
 <p> The "special deals" text has been made bold visually using CSS rather than semantically using the strong element. </p>
 <big style="font-weight:bold;">special deals</big>

<h1>Success</h1>
<p> The text "special deals" is emphasized using the strong element. </p>
<strong>special deals</strong>

<h1> Failure </h1>
<table>
 <tbody><tr><td valign="top" align="center" width="300px"><b>concert dates</b>
                </td></tr><tr bgcolor="#A9B8BF">
                    <td><b><font color="41545D">Les Garçons</font></b></td>
                    <td><b><font color="41545D">The Obelisks</font></b></td>
                  </tr>
                  <tr>
                    <td>12/2/06</td>
                    <td>24/3/06</td>
                  </tr>
   </tbody></table>
   
<h1> Success </h1>
  <table id="sfdatetable">
                     <caption>Concert Dates</caption>
                     <tbody><tr bgcolor="#A9B8BF">
                       <th scope="col">Date</th>
                       <th scope="col">Event</th>
                     </tr>
                     <tr>
                       <td>12 Feb 09</td>
                       <td lang="fr">Les Garçons</td>
                     </tr>
                     <tr>
                       <td>24 Mar 09</td>
                       <td>The Obelisks</td>
                     </tr>
                  </tbody></table> 


