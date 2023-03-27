--- 


title: fold

pdcategory: Data Math

inlets:

  1st:
  - type: float/list
    description: value to be folded
  - type: bang
    description: fold or output the last folded value (only float)
  2nd:
  - type: float
    description: lowest fold value
  3rd:
  - type: float
    description: highest fold value

outlets:

  1st:
  - type: float/list
    description: folded value(s)

arguments:
  - type: list
    description: 2 floats set min and max, 1 float sets max value (min to 0)

methods:
  - type: set <float>
    description: sets next value to be folded via bang (only float)



draft: false
---