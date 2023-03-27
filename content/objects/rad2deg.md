--- 


title: rad2deg

pdcategory: Data Math

inlets:

  1st:
  - type: float
    description: input radians value
  - type: bang
    description: convert the last value

outlets:

  1st:
  - type: float
    description: converted value in degrees

arguments:
  - type: float
    description: initial radians value



flags:
  - type: -pos
    description: wraps to positive values only

draft: false
---