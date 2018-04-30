# Day3-CSS Variables

This exercise provides us with a web page which displays an image, and has 3 form inputs from which the user can manipulate the padding, blur amount, and background color of the image. 
My goal was to update the CSS and write the JavaScript code necessary to bring functionality to the inputs 

## Guide

The purpose of this exercise is to gain experience using _CSS3 variables_. These are
  **different** from Sass-style variables; Sass variables are defined in the Sass file,
  but once compiled to CSS the values cannot be updated. _CSS3 variables_ can have
  their values updated through the use of JavaScript. The `input` _HTML elements_
  have a `name` property that corresponds with the CSS properties we want to update.
  We can create _CSS3 variable references_ and attach them to the root element, provide
  them with some default values, and utilize JavaScript to attach _event listeners_
  to the `input` _HTML elements_ that will call upon an _event handler_ function
  whenever the input values have been changed by the user. We will define the function
  to target the _entire document_ and update the values of the CSS variables
  from there.

