# chart. JS
![chart](https://cdn.mos.cms.futurecdn.net/S5bicwPe8vbP9nt3iwAwwi.jpg)
**Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.**

- great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. 

**SETTING UP**
-  download Chart.js.
- Copy the Chart.min.js out of the unzipped folder and into the directory
- create a new html page and import the script

## Drawing a line chart
- To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. 
**< canvas id="buyers" width="600" height="400"></ canvas >**

- we need to write a script that will retrieve the context of the canvas
< script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</ script>
- Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart
- data
var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}

## Drawing a pie chart
- < canvas id="countries" width="600" height="400">< /canvas>
- var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions)
- data 
var pieData = [
	{
		value: 20,
		color:"#878BB6"
	},
	{
		value : 40,
		color : "#4ACAB4"
	},
	{
		value : 10,
		color : "#FF8153"
	},
	{
		value : 30,
		color : "#FFEA88"
	}
];

## Drawing a bar chart
- < canvas id="income" width="600" height="400">< /canvas>
- var income = document.getElementById("income").getContext("2d");
new Chart(income).Bar(barData);
- data
var barData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "#48A497",
			strokeColor : "#48A4D1",
			data : [456,479,324,569,702,600]
		},
		{
			fillColor : "rgba(73,188,170,0.4)",
			strokeColor : "rgba(72,174,209,0.4)",
			data : [364,504,605,400,345,320]
		}

	]
}
# CANVAS

- **Basic usage of canvas**
< canvas id="tutorial" width="150" height="150">< /canvas>
At first sight a < canvas> looks like the < img> element, with the only clear difference being that it doesn't have the src and alt attributes
- **Fallback content**
he <canvas> element differs from an <img> tag in that, like for <video>, <audio>, or <picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers
- **Required < /canvas> tag**
As a consequence of the way fallback is provided, unlike the < img> element, the < canvas> element requires the closing tag (< /canvas>)

- **Drawing shapes with canvas**
![canvas](https://miro.medium.com/max/4558/1*6sU6aHz3-zyFpo8kscyXCQ.jpeg)
- rectangles
There are three functions that draw rectangles on the canvas:
- fillRect(x, y, width, height)
Draws a filled rectangle.
- strokeRect(x, y, width, height)
Draws a rectangular outline.
- clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.
**COLOR**
color is a string representing a CSS < color>, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black

**Drawing text**
The canvas rendering context provides two methods to render text:

- fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.



















