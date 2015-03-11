# strapdown-topbar
a topbar modification for strapdown.js
 
## Examples
Example #1
_Left aligned top links_
http://joedf.github.io/strapdown-topbar/template.html
  
Example #2
_Right aligned top links_
http://joedf.github.io/strapdown-topbar/template-right.html
  
## Usage
Have your topbar setting in the `<body>`.
```HTML
<topbar>
	<item><a href="#">Home</a></item>
	<item><a href="#">About</a></item>
	<item><small>(Powered by <a href="http://strapdownjs.com/">StrapDown.js</a>)</small></item>
</topbar>
```
Then, simply include `strapdown-topbar.js` **AFTER** `strapdown.js`.
```HTML
<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>
<!-- Include it AFTER strapdown -->
<script src="assets/strapdown/strapdown-topbar.js"></script>
```