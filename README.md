# JSONstringify
an implementation of JSON.stringify that does not evaluate getters, limits the depth of the visit, allows truncation of cycles </br>
<code>stringifyTrunc(value[,options])</code></br>
value: the value to stringify 
options:  
 depth: truncation depth (0 is the root), defaults to 2 </br>
 visit_cycles: cycles are visited if set to true, defaults to false
