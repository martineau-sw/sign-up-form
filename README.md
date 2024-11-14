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

- [x] Gather assets
	- [x] Font
	- [x] Logo
	- [x] Background image
- [x] Create index.html and style.css
- [x] Structure HTML
	- [x] Head
		- [x] Link stylesheet
		- [x] Inline font ~~Link font~~
	- [x] Splash container
		- [x] Banner container
			- [x] Odin logo
			- [x] Odin header
		- [x] Footer ~~Caption(?)~~
	- [x] Prompt
		- [x] Shill 1
		- [x] Shill 2 with emphasis
		- [ ] Form
			- [x] Form
			- [x] Fieldset
				- [x] Header/legend
				- [x] First name input field
				- [x] Last name input field
				- [x] Email input field
				- [x] Phone input field
				- [x] Password input fields, minlength
				- [x] Validate all input fields with pattern regex
					- [x] Upper-case names
					- [x] \_@\_.\_ email structure, expect username to begin with letter, case-insensitive, expect lower case letters for domain with 2-3 character TLD
					- [x] expect 10 digit phone number USA layout, either separated with hyphen or no separation
					- [x] expect any character except whitespace for password
			- [x] Submit button
		- [x] Have an account with anchor
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


#### Patterns

name pattern: `[A-Z]{1}\w*`

email pattern: `[\w]{1}[\w\d]*(@[\w]{1}[a-z0-9]+\.[a-z]{2,3})`

phone pattern: `\(?\d{3}\)?(-|.| )?\d{3}(-|.| )?\d{4}`

password pattern: `\S{8,25}`

