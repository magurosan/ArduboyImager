# ArduboyImager

##Description

ArduboyImager is a PC tool for programming Arduboy to generate bitmap data from JPEG/PNG images.

You can load an image file, scale it, adjust contrast and brightness, then crop it so as to fit to Arduboy's screen and convert it to C language source code.

Color pixels are converted to black and white dots using three differnt dithering method. (Thanks to [ofxDither](http://www.julapy.com/blog/2011/03/09/ofxdither/).)

##Instructions

Click "Open File..." button or hit space bar to open an image file. (in JPEG or PNG format)

There is a black-and-white "focus area" around mouse pointer. 

The image under focus area is automatically converted to 1-bit image and previewed in the right of the window.
You can select dithering method by clicking buttons or pressing key 1, 2, or 3.

Move pointer to locate focus to the area you want to capture, then click left button.
The image under focus area is captured and shown in the right bottom of the window.

The image can be moved by dragging. Use cursor keys to adjust focus area position in pixels.
You can change focus area size by "Width" and "Height" slider.

When image capture is done, click one of the buttons under "Copy as..." label.

"a C array" copys C source code to clipboard.
"AbShell commands" copys set of command lines for [AbShell](https://github.com/boochow/abshell). 

##Installation
ArduboyImager is developed on [openFrameworks](http://openframeworks.cc/).

You need to download and install openFrameworks 0.9.3 or newer to build ArduboyImager.

Although openFrameworks is a cross-platform toolkit, I have tested only on Windows7.
