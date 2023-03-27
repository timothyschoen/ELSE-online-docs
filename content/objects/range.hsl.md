--- 


title: range.hsl

pdcategory: UI

inlets:

  1st:
  - type: bang
    description: outputs last value
  - type: list
    description: sets range values and outputs it

outlets:

  1st:
  - type: list
    description: min/max range values



methods:
  - type: set <f, f>
    description: sets range values
  - type: width <float>
    description: sets width size
  - type: height <float>
    description: sets height size
  - type: range <f, f>
    description: sets range values
  - type: mode <float>
    description: sets mode (0  shift, 1  select, 2  expand, 3  expand)
  - type: bgcolor <f, f, f>
    description: sets background color
  - type: fgcolor <f, f, f>
    description: sets foreground color
  - type: send <symbol>
    description: sets send symbol
  - type: receive <symbol>
    description: sets receive symbol

flags:
  - type: -width <float>
    description: 
  - type: -height <float>
    description: 
  - type: -range <f, f>
    description: 
  - type: -mode <float>
    description: 
  - type: -bgcolor <f, f, f>
    description: 
  - type: -fgcolor <f, f, f>
    description: 
  - type: -send <symbol>
    description: 
  - type: -receive <symbol>
    description: 

draft: false
---