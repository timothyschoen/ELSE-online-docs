--- 


title: euclid

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: step number
  2nd:
  - type: float
    description: number of steps
  3rd:
  - type: float
    description: number of hits
  4th:
  - type: float
    description: rotation value

outlets:

  1st:
  - type: bang
    description: when there's a hit
  2nd:
  - type: bang
    description: when there's a rest
  3rd:
  - type: float
    description: 1 for hit, 0 for rest

arguments:
  - type: float
    description: number of steps
  - type: float
    description: number of hits
  - type: float
    description: rotation value





draft: false
---