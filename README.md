# JQuery load(); function in pure javascript
Added method chaining functionality so that multiple methods can be called with a single line.   

##### To load a page with _ajax.js_ >
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

#### [_See live demo_](https://github.com/md-riaz/)