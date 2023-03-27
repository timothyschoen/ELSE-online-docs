--- 


title: numbox~

pdcategory: UI

inlets:

  1st:
  - type: float
    description: sets generating value
  - type: signal
    description: value to display

outlets:

  1st:
  - type: signal
    description: input when monitoring or generated values instead



methods:
  - type: set <float>
    description: sets initialization and generating value with given float or sets current value if no float is given
  - type: size <float>
    description: sets font size
  - type: width <float>
    description: sets digits width
  - type: range <float, float>
    description: sets minimum and maximum dragging values
  - type: bgcolor <f, f, f>
    description: sets background color in RGB
  - type: fgcolor <f, f, f>
    description: sets foreground color in RGB
  - type: ramp <float>
    description: sets ramp time in ms
  - type: rate <float>
    description: sets refresh rate in ms

flags:
  - type: -size <float>
    description: font size (
  - type: -set <float>
    description: sets initial generating value
  - type: -width <float>
    description: sets digit width (
  - type: -range <float, float>
    description: dragging range (
  - type: -bgcolor <f, f, f>
    description: sets background color in RGB (default 255 255 255)
  - type: -fgcolor <f, f, f>
    description: sets frontground color in RGB (default 0 0 0)
  - type: -ramp <float>
    description: sets ramp time in ms (default 10, minimum 0)
  - type: -rate <float>
    description: sets refresh rate in ms (default 100, minimum 15)

draft: false
---