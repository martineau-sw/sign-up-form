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

