# Vita Rendering Samples

## Prerequesites

In order to build samples, you need [vitasdk](https://vitasdk.org) installed in your system.

## Building

Every sample includes a CMakeLists.txt file. Go to the directory of the sample and run `cmake . && make` to build it.

## Running

Once the sample has been built, there should be a vpk file. Send the file to your vita using ftp or usb and install it.

## List

### Common
* `input`: detect user button presses. (warning: only detects one button at a time)
* `time`: manage time using vitasdk

### SDL2
* `basic`: draws a rectangle to the screen.
* `crop`: draws part of an image to the screen.
* `image`: draws entire image to the screen.
* `loop`: moves a rectangle from left side of the screen to the right
* `text`: custom font

### OpenGL
* `triangle`: draws a triangle to the screen
* `vbo`: vertex buffer object to draw triangle

## Notes

* using sdl2 will increase vpk size significantly
