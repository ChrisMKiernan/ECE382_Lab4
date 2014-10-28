## ECE382 Lab4 - Etch-a-Sketch and Pong

Goal: To use C and assembly programming to modify the given block-drawing code to create an etch-a-sketch program (2 colors of blocks) and, for added functionality, a pong game.

### Design

Fortunately, much of the design for this lab was already created in Dr Coulston's code that was supplied. What was left was to modify the code so that it didn't erase blocks after creating them (essentially allowing the user to fill the screen) and to include "color" into the code so that blocks are created and erased.

In order to allow the user to fill the space of the LCD screen, I only had to delete the line of code that called to clear the display at the end of the program. 

In order to allow the user to clear individual blocks, both the C and assembly programs had to be modified to include a "color" variable. In C, I made the color variable take on the value of 2 or 3 (these were easy to use because I could define them as "black" and "white"). 
