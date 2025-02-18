
## Class: Canvas

A class to represent a canvas where items can be added and drawn.

### Attributes:

**function\_map** (dict): A dictionary mapping functions to controller buttons.  
**button\_map** (dict): A dictionary mapping button names to their respective codes.  
**gamepad** (InputDevice or None): The gamepad device in "board" mode, None if not found.

### Methods:

* \_\_init\_\_(backgroundcolor=(0, 0, 0), fps=30, limitFps=True, renderMode="")  
  * Initializes a Canvas object with the specified background color, fps, and rendering mode.  
  * Parameters:  
    * backgroundcolor (tuple, optional): The RGB color value to fill the canvas with. Defaults to (0, 0, 0).  
    * fps (int, optional): Frames per second for rendering. Defaults to 30\.  
    * limitFps (bool, optional): Whether to limit the frames per second. Defaults to True.  
    * renderMode (str, optional): The rendering mode. Defaults to an empty string.  
* clear()  
  * Clears the canvas by filling it with black.  
  * Parameters:  
    * None  
  * Returns:  
    * None  
* fill(fillcolor)  
  * Fills the canvas with the specified color.  
  * Parameters:  
    * fillcolor (tuple): The color to fill the canvas with.  
  * Returns:  
    * None  
* get\_points()  
  * Returns a 2D array of points representing a grid on the canvas.  
  * Returns:  
    * np.ndarray: A 2D array of points representing a grid on the canvas.
