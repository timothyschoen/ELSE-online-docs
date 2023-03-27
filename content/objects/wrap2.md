--- 


title: wrap2

pdcategory: Data Math

inlets:

  1st:
  - type: float/list
    description: value to be wrapped
  - type: bang
    description: fold or output the last wrapped value (only float)
  2nd:
  - type: float
    description: lowest wrap value
  3rd:
  - type: float
    description: highest wrap value

outlets:

  1st:
  - type: float/list
    description: 

arguments:
  - type: list
    description: 2 floats — min/max, 1 float — max

methods:
  - type: set <float>
    description: sets the next value to be wrapped via bang



draft: false
---