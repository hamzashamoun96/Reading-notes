# Charts
* Charts ar a better way to display data analysis than tables, also they are easy to look to but they are not easy to create.
* Chart.js is a JavaScript plugin that uses HTML5 canvas element to draw the graph onto th page.
* In oredr to begin we must download Chart.js , then by using < canvas> element we can make a line chart, pie chart, bar chart.
* < canvas> element it looks like a < img> element from the first time but the different between them is that canvas element don't have a (src , alt) attributes, also it has a closing tag.
* The canvas element is initially blank and to display something a script first needs to access to it (getElementById), and it has a method called ( getContext() ) which takes one parameter.
* We can draw a rectangle using a canvas element with some functions like (fillRect(), clearRect(), strokeRect()).
* We can draw a paths using canvas element with fuvtions like (closePath(), stroke(), beginPath(), fill()).
* LineTo(x, y) use to draw line, arc() or arcTo() used to draw an Arcs.
# Colors
* There are two important properties we can use: fillStyle sets the style used when filling shapes, and strokeStyle Sets the style for shapes' outlines.
* Transparency can be done by using globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.
# Styling Text 
* There are some more properties which let you adjust the way the text gets displayed on the canvas: (font = value) , (textAlign = value) , (textBaseline = value) , (direction = value)