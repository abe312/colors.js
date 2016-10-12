> colors.js

## Requirements:
* jquery (link included in `usage`)

## Usage:
* copy colors.js into your project directory
* add id="colors" to the element you want to colorify 
* add the following code into `<head>`:


`<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>`

`<script type="text/javascript" src="/path/to/color.js" charset="utf-8"></script>`

## Example html file

```html
<!DOCTYPE html>
<html>
	<head>
		<title>highlight</title>
		
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
	 <script type="text/javascript" src="main.js" charset="utf-8"></script>
		 <link href="main.css" type="text/css"  rel="stylesheet"/>
		 
	</head>
	<body>
	<p id="color">
    Lorem black orange ipsum dolor sit red amet, consectetuer adipiscing elit.
    
    Quisque bibendum sem ut lacus. Integer dolor ullamcorper libero.
    Aliquam rhoncus eros at augue. Suspendisse vitae mauris.
	red red red red red green yellow
	
	</p>
	
	</body>
</html>
```
