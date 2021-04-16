# Basic usage of canvas

Let's start this tutorial by looking at the \<canvas> HTML element itself. At the end of this page, you will know how to set up a canvas 2D context and have drawn a first example in your browser.

## The \<canvas> element
\<canvas id="tutorial" width="150" height="150">\</canvas>
At first sight a \<canvas> looks like the \<img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the \<canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

Note: If your renderings seem distorted, try specifying your width and height attributes explicitly in the \<canvas> attributes, and not using CSS.

The id attribute isn't specific to the \<canvas> element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance). It is always a good idea to supply an id because this makes it much easier to identify it in a script.

The \<canvas> element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas. We'll see how this is done in a dedicated chapter of this tutorial. When no styling rules are applied to the canvas it will initially be fully transparent.

# Drawing shapes with canvas
## The grid
Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default.

# Colors
Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

fillStyle = color <br>
Sets the style used when filling shapes.<br>
strokeStyle = color<br>
Sets the style for shapes' outlines.<br>
color is a string representing a CSS \<color>, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).

# Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])<br>
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.<br>
strokeText(text, x, y [, maxWidth])<br>
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.