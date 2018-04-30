# Day6-Type Ahead AJAX

We are given a web page with an `input` HTML element in which the user can insert
text, and an `unordered list` below that `input` which will display cities & states
that contain the text inputted by the user with a highlight around the text that
was matched. Currently, **none of that works**. 
In the `script` tag, we're provided with  a `constant` 'endpoint' that points to a JSON data collection containing the data we want 
to work with. 

## Guide

Write the necessary JavaScript code to bring functionality to this search.

Declare a variable which will contain an array and **fetch** the data from the provided endpoint,
_pushing_ the return values into the array. We'll need to attach an _event listener_ to the
`input` HTML element that will listen for the 'keyup' event, and call a yet-to-be-defined
_event handler_ function that will be responsible for formatting the data and displaying it
on the page. Within the body of the _event handler_ function we will call upon another
function (which we will define) that will be responsible for matching the inputted text 
and the values we received from the endpoint. 
How do we match the data from the endpoint with the user's inputs?
