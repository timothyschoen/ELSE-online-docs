--- 


title: eqdiv

pdcategory: Tuning

inlets:

  1st:
  - type: bang
    description: generate scale
  - type: float
    description: set number of divisions and generate scale
  2nd:
  - type: float
    description: set interval ratio

outlets:

  1st:
  - type: list
    description: scale in cents or ratio

arguments:
  - type: float
    description: number of equal divisions
  - type: float
    description: interval ratio



flags:
  - type: -ratio
    description: sets scale output to ratio instead of cents

draft: false
---