## Class: Polygon

Represents a polygon with a specified set of vertices and color.

### Attributes:

**vertices**: A list of vertices that define the polygon.  
**color**: The color of the polygon.  
**path**: The path object representing the polygon.  
**center**: The centroid of the polygon.

### Methods:

* \_\_init\_\_(vertices, color)  
  * Initializes the polygon with vertices and color.  
  * Parameters:  
    * vertices (list): A list of vertices that define the polygon. Must have at least 3 vertices.  
    * color (tuple, optional): The color of the polygon. Defaults to (255, 255, 255).  
  * Raises:  
    * ValueError: If the number of vertices is less than 3\.  
* contains\_points(points)  
  * Checks if the given points are inside the polygon.  
  * Parameters:  
    * points (np.ndarray): An array of points to check.  
  * Returns:  
    * np.ndarray: A boolean array indicating whether each point is inside the polygon.  
* translate(dx, dy)  
  * Translates the polygon by a specified distance.  
  * Parameters:  
    * dx (float): The distance to translate along the x-axis.  
    * dy (float): The distance to translate along the y-axis.  
* rotate(angle\_degrees, center)  
  * Rotates the polygon by a specified angle around a given center.  
  * Parameters:  
    * angle\_degrees (float): The angle by which to rotate the polygon (in degrees).  
    * center (tuple, optional): The center of rotation (default is (0, 0)).  
* update\_path()  
  * Updates the path of the polygon based on its current vertices.  
  * Parameters:  
    * None	  
* calculate\_center()  
  * Calculates the centroid of the polygon.  
  * Parameters:  
    * None  
  * Returns:  
    * tuple: The coordinates of the centroid.  
* get\_polygon\_mask(shape)  
  * Creates a binary mask for the polygon on a given image shape.  
  * Parameters:  
    * shape (tuple): The shape of the image (height, width).  
  * Returns:  
    * np.ndarray: A binary mask with the polygon filled in.  
* get\_center()  
  * Returns the centroid of the polygon.  
  * Parameters:  
    * None  
  * Returns:  
    * tuple: The coordinates of the centroid.
