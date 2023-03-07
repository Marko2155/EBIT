# EBIT
A C# library for making 4x4 pixel art.

# Jump to a section
[Install](https://github.com/Marko2155/EBIT#install)

[How to use](https://github.com/Marko2155/EBIT#how-to-use)

[Credits](https://github.com/Marko2155/EBIT#credits)

[Why EBIT is named EBIT](https://github.com/Marko2155/EBIT#why-ebit-is-named-ebit)

[EBIT Examples](https://github.com/Marko2155/EBIT#ebit-examples)

# Install
First, open up Visual Studio and make a new WinForms C# project. It needs to be WinForms C# because the pixels are actually giant PictureBoxes.

Second, download the .cs file from the Releases page. Place it into the root folder of your project and if the .cs file doesn't pop up, restart Visual Studio.

Third, reference EBIT by typing in:
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

If you want to set the background:
```
EBIT.EBIT.set_background(this, color);
```

# Credits
@Marko2155 - Making EBIT.

@paul0warren - For helping with the math.

# Why EBIT is named EBIT.
So, the idea is the pixels in the 4x4 grid are made from an 8x8 grid of bits, and all the bits form 1 pixel.

# EBIT Examples
- 4x4 Mario
![Mario Example](/examples/mario.png)
- 4x4 Link
![Link Example](/examples/link.png)
