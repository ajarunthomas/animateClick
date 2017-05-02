# animateClick
 jQuery plugin to create animation on mouse click
<br>
Developed by Arun Thomas
<br>
www.ajarunthomas.com
<br>
<br>
<a href="http://www.ajarunthomas.com/jquery/animateClick/demo/" target="_blank" style="text-decoration:none">Demo</a>
<a download href="http://www.ajarunthomas.com/files/animateClick.js" target="_blank" style="text-decoration:none">Download</a>
<br><br>
<a href="http://www.ajarunthomas.com/jquery/animateClick/" target="_blank" style="text-decoration:none">Website</a>
## USAGE
### Step 1 : Include js
```
<script type="text/javascript" src="js/jquery-1.12.0.min.js"></script>
<script type="text/javascript" src="js/animateClick.js"></script>
```
### Step 2 : Activate Plugin
```
$(document).ready(function() {
    $('#btn').animateClick();
});
```
### more options
If you want to create a blue signal animation with a size of 12 then
```
$(document).ready(function() {
    $('#btn').animateClick({
        "color":"blue",
        "animation":"signal",
        "size":12
    });
});
```
animations available
<br>
1. Default animation if you don't specify one 
<br>
2. signal 
<br>
3. shoot 
<br>
4. tick 
<br>
5. cross
