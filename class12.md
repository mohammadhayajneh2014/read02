#  CHARTS
: it’s better to use charts to display informations rather than using tabels, and below the steps for setting up a chart
-  Pie and Doughnut
-  line 
- bar 
- Scatter
- Polar Area
- Bubble

# canvas :
(canvas) element has only two attributes, width and height. These are both optional and can also be set

# Drawing shapes with canvas:

- The first step to create a path is to call the beginPath(). Internally, paths are stored as a list of sub-paths (lines, arcs, etc) which together form a shape. Every time this method is called, the list is reset and we can start drawing new shapes
- The second step is calling the methods that actually specify the paths to be drawn
- The third, and an optional step, is to call closePath(). This method tries to close the shape by drawing a straight line from the current point to the start

# Drawing text:

function draw() { var ctx = document.getElementById(‘canvas’).getContext(‘2d’); ctx.font = ‘50px serif’; ctx.fillText(‘Hello world’, 10, 50); }
