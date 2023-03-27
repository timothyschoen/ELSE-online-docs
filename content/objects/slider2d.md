--- 


title: slider2d

pdcategory: UI

inlets:

  1st:
  - type: bang
    description: outputs last values
  - type: list
    description: sets x, y and output it

outlets:

  1st:
  - type: list
    description: x/y values



methods:
  - type: set <f,f>
    description: sets x and y
  - type: size <f>
    description: sets size
  - type: width <f>
    description: sets x (horizontal) size
  - type: height <f>
    description: sets y (vertical) size
  - type: xrange <f,f>
    description: sets x range
  - type: yrange <f,f>
    description: sets y range
  - type: line <f>
    description:  non-0 sets line visibility
  - type: grid <f>
    description: non-0 sets grid visibility
  - type: bgcolor <f,f,f>
    description: sets background color in RGB
  - type: fgcolor <f,f,f>
    description: sets foreground color in RGB
  - type: init <f>
    description: non-0 sets to init mode

flags:
  - type: -size <f>
    description: sets x/y size (
  - type: -dim <f,f>
    description: sets x/y dimensions independently (
  - type: -range
    description: sets x/y range (
  - type: -xrange/-yrange
    description: sets x/y range independently
  - type: -line <f>
    description: non-0 sets line visibility (
  - type: -grid <f>
    description: non-0 sets grid visibility (
  - type: -bgcolor <f,f,f>
    description: sets background color (
  - type: -fgcolor <f,f,f>
    description: sets foreground color (
  - type: -init <f>
    description: non-0 sets to init mode (default 0)

draft: false
---