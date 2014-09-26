firework.js
==========

A jQuery plugin to create short lived, real time, notifications to the user.

Useage
======

Include files

`<link type="text/css" rel="stylesheet" href="jquery.firework.css">`

`<script type="text/javascript" src="jquery.firework.js"></script>`

Call firework

`firework.launch(message, type [optional], display time [optional]);`

Useage examples
---------------

**Display the message "Hello world!" for 1.5 seconds.**

`firework.launch('Hello world!');`

**Display a specific message type (error, success)**

`firework.launch('Great news', 'success');`

`firework.launch('Bad news', 'error');`

**Display an error message for a 10 seconds**

`firework.launch('Read this bad news', 'error', 10000);`

**Display a firework message on the next page load (requires jQuery Cookie plugin)**

`firework.sticky('We redirected you to safety', 'success')` 
