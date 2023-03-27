--- 


title: rad2hz

pdcategory: Data Math

inlets:

  1st:
  - type: float/list
    description: radians per sample value(s)
  - type: bang
    description: convert or output the last converted value (only float)

outlets:

  1st:
  - type: float/list
    description: converted Hz value(s)

arguments:
  - type: float
    description: initial radians per sample value

methods:
  - type: set <float>
    description: sets next value to be converted via bang (only float)



draft: false
---