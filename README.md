# JSONstringify
an implementation of JSON.stringify that does not evaluate getters, limits the depth of the visit, allows truncation of cycles
 options:  
   depth: truncation depth (0 is the root), defaults to 2 <br>
   visit_cycles: cycles are visited if set to true, defaults to false
