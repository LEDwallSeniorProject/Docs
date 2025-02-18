
## Class: Pixel

Represents a single pixel with a specified position, color, and scale.

### Attributes:

**position**: The position of the pixel.  
**color**: The color of the pixel.  
**scale**: The scale of the pixel.

### Methods:

* \_\_init\_\_(position, color, scale)  
  * Initializes the pixel with position, color, and scale.  
  * Parameters:  
    * position (list): The position of the pixel.  
    * color (list, optional): The color of the pixel. Defaults to \[255, 255, 255\].  
    * Scale (int, optional): The scale of the pixel. Defaults to 1\.  
* contains\_points(points)  
  * Checks if the given points are inside the pixel.  
  * Parameters:  
    * points (np.ndarray): An array of points to check.  
  * Returns:  
    * np.ndarray: A boolean array indicating whether each point is inside the pixel.  
* translate(dx, dy)  
  * Translates the pixel by a specified distance.  
  * Parameters:  
    * dx (float): The distance to translate along the x-axis.  
    * dy (float): The distance to translate along the y-axis.
