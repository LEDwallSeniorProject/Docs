
## Class: Image (inherits from ColoredBitMap)

Represents an image loaded from an external source, with a specified position and size.

### Attributes:

**width**: The width of the image.  
**height**: The height of the image.  
**position**: The position of the image.  
**scale**: The scale of the image.

### Methods:

* \_\_init\_\_(width, height, position, scale)  
  * Initializes the colored image with width, height, position, and scale.  
  * Parameters:  
    * width (int): The width of the bitmap.  
    * height (int): The height of the bitmap.  
    * position (list, optional): The position of the bitmap. Defaults to \[0, 0\].  
    * scale (int, optional): The scale of the bitmap. Defaults to 1\.  
* loadfile(filename)  
  * Loads an external file into the class. If the image is not the specified width and height, the image will be automatically resized.  
  * Parameters:  
    * filename (str): The filename of the image to load  
* loadpixels(pixels)  
  * Loads a list of RGB colored pixels (one dimensional)  
  * Parameters:  
    * pixels (list): A 1D list of RGB tuples that comprise the image
