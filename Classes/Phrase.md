
## Class: Phrase

Represents a phrase composed of multiple letters.

### Attributes:

**text**: The text of the phrase.  
**position**: The position of the phrase.  
**color**: The color of the phrase.  
**size**: The size of the phrase.  
**auto\_newline**: Whether to automatically wrap the text to a new line.  
**letters**: The list of letters in the phrase.

### Methods:

* \_\_init\_\_(text, position, color, size, auto\_newline)  
  * Initializes the phrase with text, position, color, size, and auto\_newline.  
  * Parameters:  
    * text (str): The text of the phrase.  
    * position (list, optional): The position of the phrase. Defaults to \[0, 0\].  
    * color (list, optional): The color of the phrase. Defaults to \[255, 255, 255\].  
    * size (int, optional): The size of the phrase. Defaults to 1\.  
    * auto\_newline (bool, optional): Whether to automatically wrap the text to a new line. Defaults to False.  
* set\_text(text)  
  * Updates the text of the phrase.  
  * Parameters:  
    * text (str): The new text of the phrase.  
* set\_position(position)  
  * Updates the position of the phrase.  
  * Parameters:  
    * position (list): The new position of the phrase	.  
* get\_width()  
  * Returns the width of the phrase.  
  * Parameters:  
    * None  
  * Returns:  
    * int: The width of the phrase.  
* translate(dx, dy)  
  * Translates the phrase by a specified distance.  
  * Parameters:  
    * dx (float): The distance to translate along the x-axis.  
    * dy (float): The distance to translate along the y-axis.  
* get\_letters()  
  * Creates the letters based on the text and position.  
  * Parameters:  
    * None  
  * Returns:  
    * list: A list of Letter objects representing the letters in the phrase.  
    * update\_letters(new\_text)  
* Updates the letters based on the new text.  
  * Parameters:  
    * new\_text (str): The new text of the phrase.  
* update\_positions()  
  * Updates the positions of all letters based on the new starting position.  
  * Parameters:  
    * None  
* contains\_points(points)  
  * Checks if the given points are inside the phrase.  
  * Parameters:  
    * points (np.ndarray): An array of points to check.  
  * Returns:  
    * np.ndarray: A boolean array indicating whether each point is inside the phrase.
