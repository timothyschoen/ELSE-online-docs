--- 


title: ratio2cents

pdcategory: Data Math

inlets:

  1st:
  - type: float/list
    description: rational value(s)
  - type: bang
    description: convert or output the last converted value (only float)

outlets:

  1st:
  - type: float/list
    description: converted cents value(s)

arguments:
  - type: float
    description: initial rational value

methods:
  - type: set
    description: sets next value to be converted via bang (only float)



draft: false
---