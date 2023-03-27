--- 


title: colors

pdcategory: UI

inlets:

  1st:
  - type: bang
    description: output/convert color

outlets:

  1st:
  - type: anything
    description: color values (in RGB, hex, iemgui or ds)



methods:
  - type: pick
    description: open color picker
  - type: rgb <f, f, f>
    description: RGB (Red, Green, Blue) color values
  - type: hex <symbol>
    description: hexadecimal color value
  - type: iemgui <float>
    description: iemgui's color format value
  - type: ds <float>
    description: Data Structures' color value
  - type: cmyk <f, f, f, f>
    description: CMYK (Cyan, Magenta, Yellow, and Key) color values
  - type: hsl <f, f, f>
    description: HSL (Hue, Saturation, and Lightness) color values
  - type: hsv <f, f, f>
    description: HSV (Hue, Saturation, and Value) color values
  - type: gray <float>
    description: grayscale value from 0 to 100
  - type: to <symbol>
    description: set conversion to "rgb," "hex," "gui" or "ds

flags:
  - type: -rgb
    description: sets to RGB list output (default hexadecimal)
  - type: -iemgui
    description: sets to iemguis output (default hexadecimal)
  - type: -ds
    description: sets to Data Structures output (default hexadecimal)

draft: false
---