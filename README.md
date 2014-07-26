css-monkey
==========

![Monkey](http://www.10134.dk/images/monkey.png "Monkey")

A monkey, animated with rolling eyes, build with CSS.

The monkey is created as an easteregg for my websites, therefore you must hover above an area of 10x10 pixels, in the upper-right corner of the website, to reveal the monkey. A __demonstration__ can be found at [www.aybabtu.dk](http://www.aybabtu.dk)

### How to add the monkey to your website

1: Add the HTML tags from index.html to your site

```html
<div class="monkey-trigger">
	<div class="monkey">
		<div class="hair"></div>
		<div class="head">
			<div class="ear left"></div>
			<div class="ear right"></div>
			<div class="face">
				<div class="eye left"></div>
				<div class="eye right"></div>
				<div class="nose"></div>
				<div class="mouth"></div>
			</div>
		</div>
	</div>
</div>
```

2: include monkey.css

```html
<link rel="stylesheet" type="text/css" href="stylesheets/monkey.css">
```

### Modify easily
#### Size
The monkey is fully scalable to any size! Simply modify the $scale variable in monkey.scss to change the size of the monkey (and recompile the SASS file).

#### Color
monkey.scss contains variables for each color used. Simply change the color codes for these and recompile the SASS file, to change the color of the monkey.
