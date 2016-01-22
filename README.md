#Minify Menu
Pure CSS approach to minify - or toggle - a menu

##Demo
Visit the [Demo](http://lucaspacheco.github.io/minify-menu/) page.

##Getting started
Clone or download, or get the single [minify-menu.min.css](https://raw.githubusercontent.com/lucaspacheco/minify-menu/master/css/minify-menu.min.css)

###Min Example
```html
<!DOCTYPE html>
<html lang="pt-Br">
<head>
	<link rel="stylesheet" href="css/minify-menu.css">
</head>

<body>
  	<input type="checkbox" name="toogleSidebar" id="toogleSidebar" value="true" class="hidden">
  	<header class="sidebar" >
  		...
  	</header>
  	<main class="main">
  		...
  	</main>
</body>
</html>
```

##Limitations
* CSS3 transitions don't apply.