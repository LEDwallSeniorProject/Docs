
## Class: Controller

A class to represent a controller for handling input events. The layout for both board and debug modes is mapped as follows:  
Player 1:

Player 2:

\# Keyboard to controller mappings:  
Player1:

Player 2:

### Attributes:

**vertices (np.ndarray):** A numpy array of vertices that define the polygon.  
**color (tuple):** The color of the polygon in RGB format.  
**path (matplotlib.path.Path):** The path object representing the polygon.

### Methods:

* \_\_init\_\_(self)

  * Initializes the Controller object.  
  * Parameters:  
    * self  
* add\_function(self, button, function)  
  * Maps a function to a specific button.  
  * Parameters:  
    * button (str): The name of the button to map (e.g., "LB", "RB", "A", etc.).  
    * function (callable): The function to be executed when the specified button is pressed.  
* check\_key\_presses(self)  
  * Checks for button presses and calls mapped functions.  
  * In board mode: Reads events from the gamepad and checks for key press events. If a mapped button is pressed, the corresponding function is called.  
  * In debug mode: Checks for KEYDOWN events in pygame. If a mapped key is pressed, the corresponding function is called.
 

### Keyboard Mappings
#### Player 1

`"LB": "q",`

`"RB": "e"`

`"UP": "w"`

`DOWN": "s"`

`"LEFT": "a"`

`"RIGHT": "d"`

`"A": "g"`

`"B": "v"`

`"Y": "f"`

`"X": "t"`

`"SELECT": "z"`

`"START": "c"`

#### Player 2

`"LB2": "u"`

`"RB2": "o"`

`"UP2": "i"`

`"DOWN2": "k"`

`"LEFT2": "j"`

`"RIGHT2": "l"`

`"A2": "'"`

`"B2": "/"`

`"Y2": ";"`

`"X2": "["`

`"SELECT2": "m"`

`"START2": "."`

