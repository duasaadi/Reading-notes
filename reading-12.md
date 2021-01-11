# Canvas:
An attribute used to create different types of charts the `<canvas>` element has only two attributes, width and height
The `<canvas>` element can be styled just like any normal image (margin, border, background…). differs from an `<img>` tag in that, like for `<video>`, `<audio>`, or `<picture>` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.
# The rendering context:
 To display something, a script first needs to access the rendering context and draw on it. The `<canvas>` element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context and specify "2d" to get a `CanvasRenderingContext2D`.
 ![sample](img/sample.PNG)
 # Drawing Shapes:
  `<canvas>` only supports two primitive shapes: rectangles and paths,  There are three functions that draw rectangles on the canvas:
  * `fillRect(x, y, width, height)` to draw a filled rectangle.
  * `strokeRect(x, y, width, height)` to draw rectangle outeline.
  * `clearRect(x, y, width, height)` making it transparent.
   steps to draw path:
   * `beginPath()` Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
   * `closePath()` add straight line to path.
   * `stroke()` Draws the shape by stroking its outline.
   * `fill()` Draws a solid shape by filling the path's content area.
   * final  and an optional step, is to call `closePath()`. This method tries to close the shape by drawing a straight line from the current point to the start.
   # Drawing text:
    two methods to render text:
    * `fillText(text, x, y [, maxWidth])` Fills a given text at the given (x,y) position.
    * `strokeText(text, x, y [, maxWidth])` Strokes a given text at the given (x,y) position.
    ![](img/draw-text)

 