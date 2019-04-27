# JQuery load(); function in pure javascript
Added method chaining functionality so that multiple methods can be called with a single line.   

##### 1. To load a page with _ajax.js_ >
- add **'ajax.js'** file with a script tag  
- select the element where ajax responce will load with **'loc()'** function  
- set _location_ of a page from where data will load asynchronously  

## Example :-

```<script src="ajax.js"></script>```  
```
<script>
loc("#content").ajax("contents/home.html");
</script>
```

### Code differences in _JQuery.js_ vs ajax.js---

### In JQuery, code is:
'$("#content").load("contents/home.html");'

### & In _ajax.j_s, code is:
'loc("#content").ajax("contents/home.html");'  

##### 2. To prevent navigation links from following link on **href** >  
- set a tag list with selector in **nav()** function  
- add dot**(.)** symbol with **nav()** function  
- write **prevent()** all in a single line.  

## Example :-

```
nav("div.topnav a").prevent();
```

#### [_See live demo_](https://md-riaz.github.io/JQuery_load_with_js/)