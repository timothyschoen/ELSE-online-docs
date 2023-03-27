--- 


title: hz2rad

pdcategory: Data Math

inlets:

  1st:
  - type: float/list
    description: Hz value(s)
  - type: bang
    description: convert or output the last converted value (only float)

outlets:

  1st:
  - type: float/list
    description: converted radians per sample value(s)

arguments:
  - type: float
    description: initial frequency value

methods:
  - type: set
    description: sets next value to be converted via bang (only float)



draft: false
---