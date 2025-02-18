
## Class: BitMap

Represents a bitmap with a specified color.

### Attributes:

**pixels**: The list of pixels in the bitmap.  
**width**: The width of the bitmap.  
**height**: The height of the bitmap.  
**position**: The position of the bitmap.  
**color**: The color of the bitmap.  
**scale**: The scale of the bitmap.  
**cached\_points**: Cached points for optimization.  
**cached\_mask**: Cached mask for optimization.  
**cached\_points\_x**: Cached x-coordinates of points.  
**cached\_points\_y**: Cached y-coordinates of points.

### Methods:

* \_\_init\_\_(pixels, width, height, position, color, scale)  
* Initializes the bitmap with pixels, width, height, position, color, and scale.  
  * Parameters:  
    * pixels (list): The list of pixels in the bitmap.  
    * width (int): The width of the bitmap.  
    * height (int): The height of the bitmap.  
    * position (list, optional): The position of the bitmap. Defaults to \[0, 0\].  
    * color (list, optional): The color of the bitmap. Defaults to (255, 255, 255).  
    * scale (int, optional): The scale of the bitmap. Defaults to 1\.  
* contains\_points(points)  
  * Checks if the given points are inside the bitmap.  
  * Parameters:  
    * points (np.ndarray): An array of points to check.  
  * Returns:  
    * np.ndarray: A boolean array indicating whether each point is inside the bitmap.  
* translate(dx, dy)  
  * Translates the bitmap by a specified distance.  
  * Parameters:  
    * dx (float): The distance to translate along the x-axis.  
    * Dy (float): The distance to translate along the y-axis.  
* set\_bitmap(pixels, width, height)  
  * Updates the bitmap with new pixel data, width, and height.  
  * Parameters:  
    * pixels (list): The new list of pixels.  
    * width (int): The new width of the bitmap.  
    * height (int): The new height of the bitmap.  
* set\_position(position)  
  * Sets a new position for the bitmap.  
  * Parameters:  
    * position (list): The new position of the bitmap.	  
* invalidate\_cache()  
  * Invalidates the cached result of contains\_points.  
* bbox\_intersects(bbox1, bbox2)  
  * Checks if two bounding boxes intersect.  
  * Parameters:  
    * bbox1 (tuple): The first bounding box.  
    * bbox2 (tuple): The second bounding box.  
  * Returns:  
    * bool: True if the bounding boxes intersect, False otherwise.
