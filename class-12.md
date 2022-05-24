## Chart.js

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

Chart.js General:

- accessibility
- clolors
- data structures
- fonts
- options
- padding
- performance

- Chart.js
  > download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:
- Drawing a line chart
- Drawing a pie chart
- Drawing a bar chart
  


## Canvas API

The Canvas API provides a means for drawing graphics via JavaScript and the HTML ```<canvas>``` element. Among other things, it can be used for animation, game graphics, data visualization, photo manipulation, and real-time video processing.

- ```<canvas>``` element has only two attributes, width and height.
  <br>
- Canvas libraries
  <br>
- Drawing shapes with canvas: rectangles
   ```fillRect(x, y, width, height)```
Draws a filled rectangle.

   ```strokeRect(x, y, width, height)```
Draws a rectangular outline.

   ```clearRect(x, y, width, height)```
Clears the specified rectangular area, making it fully transparent.
<br>
- Applying styles and colors
<br>
   ```fillStyle = color```
Sets the style used when filling shapes.

   ```strokeStyle = color```
Sets the style for shapes' outlines.
<br>
-  Drawing text
   ```fillText(text, x, y [, maxWidth])```
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

   ```strokeText(text, x, y [, maxWidth])```
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.```