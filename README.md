# Microsoft Paint in Python

126 colors to choose from to paint with. 
Various different brushes.

Tools:
  * Brush tool:
      Normal brush tool to draw and paint with adjustable size
  * Eraser tool:
      Eraser tool to erase with adjustable eraser size
      -- If you keep pressing right click, as you draw, your selected tool becomes the eraser.
  * Fill tool:
      Fills any empty closed space with your selected color. Using the recursive flood fill algorithm.
  * Color Picker tool (Eyedropper):
      Lets you pick the color in the canvas from a single pixel.
  
  
# Shortcuts
Hotkeys:
  * CTRL + Z : Undoes your last adjustment.
  * CTRL + Space : Deletes your layer 
  * CTRL + S : Saves your work. Same as "save as".
  * B : Select brush tool.
  * E : Select eraser tool.
  * G : Select fill tool.
  * I : Select color picker / eyedropper tool.
  * Right Click : Your selected tool becomes the eraser -until you release the button-.
  * 1 and 2 : Change between the color palettes faster.

# Requirements to run
Modules:
  * Python 3.x
  * Pygame
  * Tkinter
