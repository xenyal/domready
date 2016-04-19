If you are ever writing your own JavaScript file that cannot depend on the existing libraries out there and would like to execute only after the page is loaded, this library is for you.

Simply do this:

```
<html lang="en">
<head>
	<script src="domready.js" type="application/javascript"></script>
	<script type="application/javascript">
		DomReady.ready(function() {
		    alert('dom is ready');
		});
	</script>
</head>
<body>

</body>
</html>
```

A big thanks to [John Resig and the jQuery team](http://www.jquery.com/) for the parent library and the real hard work to make sense of the browser idiosyncrasies we have today.