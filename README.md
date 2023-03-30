# Find-Relative-Mouse-Cordinates
This code uses the PyAutoGUI library to automate mouse movements and clicks. It first moves the mouse to a specified location, right-clicks the mouse, and then waits for a context menu to appear. After a delay, it gets the current mouse position and calculates the relative position between the current position and the given position.

The relative position is then printed to the console. The code can be used for tasks that involve interacting with context menus, such as right-clicking on an object and selecting an option from the menu.

Note that this code assumes that the user has manually moved the mouse to the second location after the context menu appears. If the second location can also be determined programmatically, the code can be modified to move the mouse to that location automatically.
