# SVG Intro

## SVG Predefined Shapes
* Rectangle `<rect>`
* Circle `<circle>`
* Ellipse `<ellipse>`
* Line `<line>`
* Polyline `<polyline>`
* Polygon `<polygon>`
* Path `<path>`



## SVG Attributes
* width: width of svg
* height: height of svg



## Shape Attributes
* width: width of shape
* height: height of shape
* stroke: color of the border
* stroke-width: border width
* fill: color inside the shape
* x: defines the left position of a shape relative to its container
* y: defines the top position of a shape relative to its container



### Rectangle Attributes
* rx: rounds the corner of a shape
* ry: rounds the corner of a shape



### Circle Attributes
* cx: define the x coordinate of the center of the circle
* cy: define the y coordinate of the center of the circle
* r: radius of the circle



### Ellipse Attributes
An ellipse is closely related to a circle. The difference is that an ellipse has an x and a y radius that differs from each other, while a circle has equal x and y radius

* cx: the x coordinate of the center of the ellipse
* cy: the y coordinate of the center of the ellipse
* rx: the horizontal radius
* ry: the vertical radius



### Line Attributes
* x1 the start of the line on the x-axis
* y1 the start of the line on the y-axis
* x2 the end of the line on the x-axis
* y2 the end of the line on the y-axis



### Polygon Attributes
A polygon is a graphic that contains at least three sides.

* points: the x and y coordinates for each corner of the polygon



### Polyline Attributes
The `<polyline>` element is used to create any shape that consists of only straight lines (that is connected at several points)

* points: the list of points (pairs of x and y coordinates) required to draw the polyline



### Path Attributes
The `<path>` element is used to define a path. The path is defined by it's attributes (commands). All of the following commands can also be expressed with lower letters. Capital letters means absolutely positioned, lower cases means relatively positioned.


* M: moveto
* L: lineto
* H: horizontal lineto
* V: vertical lineto
* C: curveto
* S: smooth curveto
* Q: quadratic Bézier curve
* T: smooth quadratic Bézier curveto
* A: elliptical Arc
* Z: closepath


It's best to use an svg editor to draw with path.



### Text Attributes
Use `<tspan>` for multiline text. Other than that, there's not a lot of special attributes for text.

https://www.w3schools.com/graphics/svg_text.asp

* fill: text color
* stroke: text border color



## Stroking
* stroke: color of a line
* stroke-width: thickness of a line
* stroke-linecap: different types of endings
    * `butt`
    * `round`
    * `square`
* stroke-dasharray: used to create dashed lines
