
## Class: CircleOutline (inherits from PolygonOutline)

Represents an outline of a circle with a specified thickness.

### Attributes:

**radius**: The radius of the circle outline.  
**center**: The center of the circle outline.  
**color**: The color of the circle outline.  
**thickness**: The thickness of the circle outline.

### Methods:

* \_\_init\_\_(radius, center, color, thickness)  
  * Initializes the circle outline with radius, center, color, and thickness.  
  * Parameters:  
    * radius (float): The radius of the circle outline.  
    * center (tuple): The center coordinates of the circle outline.  
    * color (tuple, optional): The RGB color values of the circle outline. Defaults to (255, 255, 255).  
    * thickness (float, optional): The thickness of the circle outline. Defaults to 1\.  
* contains\_points(points)  
  * Checks if the given points are inside the circle outline.  
  * Parameters:  
    * points (np.ndarray): An array of points to check.  
  * Returns:  
    * np.ndarray: A boolean array indicating whether each point is inside the circle outline.
