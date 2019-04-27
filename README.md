# JQueryLoad-with-javascript
added method chaining so multiple methods can be called with a single line.
To load a page with ajax >
- add 'ajax.js' file with a script tag
- select the element where ajax responce will load with 'loc()' function
- set location of a page from where data will load asynchronously

Example :-

'<script src="ajax.js"></script>'
'loc("#content").ajax("contents/home.html");'


Code differences in JQuery.js vs ajax.js---

In JQuery, code is:
'$("#content").load("contents/home.html");'

& In ajax.js, code is:
'loc("#content").ajax("contents/home.html");'