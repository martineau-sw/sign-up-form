# sign-up-form

# Project: Sign-up Form

## Overview

A modern sign-up page with some surface HTML validation to mimic sign-up user experience using techniques covered so far. 

## Problem Solving

### Understand

Create a landing page that accepts sign-up information on a form with decorative elements, validation, and form feedback according to the provided design image.

![[sign-up-form-design-image.png]]

### Plan

#### Structure and expectations

- pattern validation on all input fields
- length validation on password field
- responsive stylization for validation feedback using pseudo-classes
- flex on page, stretch alignment with 100vh
	- div for splash
		- div for logo, flex, with center alignment
		- caption
	- div element for prompt
		- paragraphs for shill
		- form, arbitrary action and method
			- fieldset
				- label and input for each data item within a div 
			- submit button
			- p login redirect

#### To do

- [ ] Gather assets
	- [ ] Font
	- [ ] Logo
	- [ ] Background image
- [ ] Create index.html and style.css
- [ ] Structure HTML
	- [ ] Splash container
		- [ ] Banner container
			- [ ] Odin logo
			- [ ] Odin header
		- [ ] Caption(?)
	- [ ] Prompt
		- [ ] Shill 1
		- [ ] Shill 2 with emphasis
		- [ ] Form
			- [ ] Form
			- [ ] Fieldset
				- [ ] Header/legend
				- [ ] First name input field
				- [ ] Last name input field
				- [ ] Email input field
				- [ ] Phone input field
				- [ ] Password input fields, minlength
				- [ ] Validate all input fields with pattern regex
					- [ ] Upper-case names
					- [ ] \_@\_.\_ email structure, expect username to begin with letter, case-insensitive, expect lower case letters for domain with 2-3 character TLD
					- [ ] expect 10 digit phone number USA layout, either separated with hyphen or no separation
					- [ ] accept 
			- [ ] Submit button
		- [ ] Have an account with anchor
- [ ] Responsive style guide
	- [ ] Body(?)
		- [ ] Flex
	- [ ] Banner container
		- [ ] Transparent background color
		- [ ] Flex
	- [ ] input
		- [ ] :valid(?)
		- [ ] :invalid & ::after (combine somehow?)
		- [ ] :focus(?)
	

