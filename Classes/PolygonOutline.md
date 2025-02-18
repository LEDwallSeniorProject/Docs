
## Class: PolygonOutline (inherits from Polygon)

Represents an outline of a polygon with a specified thickness.

### Attributes:

**vertices**: The vertices of the polygon.  
**color**: The color of the polygon outline.  
**thickness**: The thickness of the polygon outline.  
**center**: The centroid of the polygon.  
**inner\_vertices**: The vertices of the inner polygon.

### Methods:

* \_\_init\_\_(vertices, color, thickness)  
  * Initializes the polygon outline with vertices, color, and thickness.  
  * Parameters:  
    * vertices (list): A list of vertices that define the polygon.  
    * color (tuple, optional): The color of the polygon outline. Defaults to (255, 255, 255).  
    * thickness (float, optional): The thickness of the polygon outline. Defaults to 1\.  
* change\_inner\_vertices(inner\_vertices)  
  * Changes the inner vertices of the polygon outline.  
  * Parameters:  
    * inner\_vertices (list): A list of vertices that define the inner polygon.  
* rotate\_inner(angle\_degrees, center)  
  * Rotates the inner polygon by a specified angle around a given center.  
  * Parameters:  
    * angle\_degrees (float): The angle by which to rotate the inner polygon (in degrees).  
    * center (tuple, optional): The center of rotation (default is (0, 0)).  
* rotate(angle\_degrees, center)  
  * Rotates the polygon outline by a specified angle around a given center.  
  * Parameters:  
    * angle\_degrees (float): The angle by which to rotate the polygon outline (in degrees).  
    * center (tuple, optional): The center of rotation (default is (0, 0)).  
* distance(x1, y1, x2, y2)  
  * Calculates the distance between two points.  
  * Parameters:  
    * x1 (float): The x-coordinate of the first point.  
    * y1 (float): The y-coordinate of the first point.  
    * x2 (float): The x-coordinate of the second point.  
    * y2 (float): The y-coordinate of the second point.  
  * Returns:  
    * float: The distance between the two points.  
* contains\_points(points)  
  * Checks if the given points are inside the polygon outline.  
  * Parameters:  
    * points (np.ndarray): An array of points to check.  
  * Returns:  
    * np.ndarray: A boolean array indicating whether each point is inside the polygon outline.
