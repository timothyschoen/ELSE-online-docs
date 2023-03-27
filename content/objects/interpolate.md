--- 


title: interpolate

pdcategory: Data Math

inlets:

  1st:
  - type: float
    description: interpolation value between 0 and 1
  2nd:
  - type: list
    description: sets target values

outlets:

  1st:
  - type: list
    description: interpolated values

arguments:
  - type: list
    description: sets start value(s)

methods:
  - type: start <list>
    description: set start value(s)
  - type: target <list>
    description: set target value(s)
  - type: exp <float>
    description: sets exponential factor

flags:
  - type: -exp <float>
    description: sets exponential factor (default 1)

draft: false
---