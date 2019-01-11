# Littlefoot Library (WIP)

A collection of reusable Littlefoot functions.

> NOTE: files prefixed with `lib` contain only function definitions and are designed to be used with `#include` directive to make these functions available for your scripts.

## Colour Tools

### • makeARGBfromAHSV()
```c++
int makeARGBfromAHSV(int alpha, int hue, int sat, int val)
```

Combines a set of 8-bit AHSV values into a 32-bit colour and returns the result.

| Returns | 
|-|
| A 32-bit colour |

|     Parameters    | Description |
|-|-|
| alpha   | The alpha in range 0 - 255 inclusive |
| hue     | The hue in range 0 - 255 inclusive   |
| sat     | The saturation in range 0 - 255 inclusive |
| val     | The value (brightness) in range 0 - 255 inclusive |
