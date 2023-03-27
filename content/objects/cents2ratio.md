--- 


title: cents2ratio

pdcategory: Tuning

inlets:

  1st:
  - type: float/list
    description: cents value(s)
  - type: bang
    description: convert or output the last converted value (only float)

outlets:

  1st:
  - type: float/list
    description: converted ratio value(s)

arguments:
  - type: float
    description: initial cents value

methods:
  - type: set <float>
    description: sets next value to be converted via bang (only float)



draft: false
---