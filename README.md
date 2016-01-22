#Minify Menu
Pure CSS approach to minify - or toggle - a menu

##Demo
Visit the [Demo](http://lucaspacheco.github.io/minify-menu/) page.

##Getting started
Clone or download, or get the single [minify-menu.min.css](https://raw.githubusercontent.com/lucaspacheco/minify-menu/master/css/minify-menu.min.css) and call it on you document.
Here is a minimum example:
```html
<!DOCTYPE html>
<html lang="pt-Br">
<head>
	<link rel="stylesheet" href="css/minify-menu.css">
</head>

<body>
  	<input type="checkbox" id="toogleSidebar" style="displa:none">
  	<header class="sidebar" >
  		...
  		<label for="toogleSidebar">
			Close | Open
		<label>
  	</header>
  	<main class="main">
  		...
  	</main>
</body>
</html>
```
### !important stuff
* The **input** ID must match the css selector. If for some reason you _need_ to use a diferent one replace the `id="toogleSidebar"` at html and the `#toogleSidebar` at CSS file as well.
 * It also need to be hidden. The `example.css` file presents an simple class `.hidden {display:none}`. But you can also do that another way.
* The `.sidebar` element must follow right after the input line. That way the selector `#toogleSidebar:checked + .sidebar` will work properly.
* Since the input is hidden, you need to use some label that will toogle the checkbox. Remember to pass the input id as `value` the `for` attribute. Ex: `<label for="toogleSidebar">`


##Limitations _a.k.a Know Issues_
* CSS3 transitions don't apply