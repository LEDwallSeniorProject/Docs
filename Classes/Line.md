
## Class: Line (inherits from Polygon)

Represents a line segment with a specified start and end point, color, and thickness.

### Attributes:

**start**: The start point of the line.  
**end**: The end point of the line.  
**thickness**: The thickness of the line.  
**length**: The length of the line.  
**angle**: The angle of the line.

### Methods:

* \_\_init\_\_(start, end, color, thickness)  
  * Initializes the line with start and end points, color, and thickness.  
  * Parameters:  
    * start (list): The start point of the line.  
    * end (list): The end point of the line.  
    * color (list, optional): The color of the line. Defaults to (255, 255, 255).  
    * thickness (float, optional): The thickness of the line. Defaults to 0.5.  
  * Raises:  
    * ValueError: If the start and end points are the same, thickness is less than or equal to zero, or the start/end points or color are not of the correct length.  
* calculate\_angle()  
  * Calculates the angle of the line.  
  * Parameters:  
    * None  
  * Returns:  
    * float: The angle of the line in degrees.
