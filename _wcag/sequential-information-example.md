---
id: 139
title: Sequential Information Example
date: 2014-02-12T07:34:27+00:00
author: Manish
layout: page
guid: https://13.68.136.88//?page_id=139
page_location:
  - 'No'
---
		
		<h3>Tab Sequence - Failure</h3>
		<div class="row">
			<form>
			  <div class="span6">
			  	<legend>Husband Details</legend>
				<label>First Name</label>
				<input type="text" placeholder="First Name" tabindex="1">
				<label>Last Name</label>
				<input type="text" placeholder="Last Name" tabindex="3">
				<label>Email</label>
				<input type="text" placeholder="Email" tabindex="5">
			  </div>
			  <div class="span6">
				<legend>Wife Details</legend>
				<label>First Name</label>
				<input type="text" placeholder="First Name" tabindex="2">
				<label>Last Name</label>
				<input type="text" placeholder="Last Name" tabindex="4">
				<label>Email</label>
				<input type="text" placeholder="Email" tabindex="6">
			  </div>
			</form>
		</div>
		
		<h3>Tab Sequence - Success</h3>
		<div class="row">
			<form>
			  <div class="span6">
			  <fieldset>
				<legend>Husband Details</legend>
				<label>First Name</label>
				<input type="text" placeholder="First Name">
				<label>Last Name</label>
				<input type="text" placeholder="Last Name">
				<label>Email</label>
				<input type="text" placeholder="Email">
			  </fieldset>
			  </div>
			  <div class="span6">
			  <fieldset>
				<legend>Wife Details</legend>
				<label>First Name</label>
				<input type="text" placeholder="First Name">
				<label>Last Name</label>
				<input type="text" placeholder="Last Name">
				<label>Email</label>
				<input type="text" placeholder="Email">
			  </fieldset>
			  </div>
			</form>
		</div>
	
    <script src="../js/jquery.js"></script>
    <script src="../js/bootstrap.js"></script>
