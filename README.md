# EBIT
A C# library for making 4x4 pixel art.

# Install
First, open up Visual Studio and make a new WinForms C# project. It needs to be WinForms C# because the pixels are actually giant PictureBoxes.
Second, download the .cs file from the Releases page. Place it into the root folder of your project and if the .cs file doesn't pop up, restart Visual Studio.
Third, reference EBIT by typing in
```
using EBIT;
```

# How to use
First, initialize EBIT by clicking on the form and typing:
```
EBIT.EBIT.init(this, "EBIT Program", Color.White);
```
You can change the "White" in "Color.White" to anything.
Now you can draw pixels to the screen.
Type in:
```
EBIT.EBIT.draw_pixel(this, 0, 0, Color.Red);
```
Here's the structure of the command:
```
EBIT.EBIT.draw_pixel(this, x, y, Color.[color]
```
X can only be 0-3 (or 1-4).
Y can only be 0-3 (or 1-4).

# Credits
@Marko2155 - Making EBIT.
@paul0warren - For helping with the math.
