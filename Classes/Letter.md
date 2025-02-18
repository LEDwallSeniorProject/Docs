
## Class: Letter (inherits from BitMap)

Represents a single letter with a specified character, position, color, and size.

### Attributes:

**char**: The character of the letter.  
**mask**: The mask representing the letter.  
**position**: The position of the letter.  
**color**: The color of the letter.  
**size**: The size of the letter.

### Methods:

* \_\_init\_\_(char, position, color, size)  
  * Initializes the letter with character, position, color, and size.  
  * Parameters:  
    * char (str): The character of the letter.  
    * position (list, optional): The position of the letter. Defaults to \[0, 0\].  
    * color (list, optional): The color of the letter. Defaults to \[255, 255, 255\].  
    * size (int, optional): The size of the letter. Defaults to 1\.  
* set\_char(new\_char)  
  * Updates the character of the letter.  
  * Parameters:  
    * new\_char (str): The new character of the letter.  
* set\_position(new\_position)  
  * Updates the position of the letter.  
  * Parameters:  
    * new\_position (list): The new position of the letter.  
* set\_color(new\_color)  
  * Updates the color of the letter.  
  * Parameters:  
    * new\_color (list): The new color of the letter.  
* get\_width()  
  * Returns the width of the letter.  
  * Parameters:  
    * None  
  * Returns:  
    * int: The width of the letter.
