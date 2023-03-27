--- 


title: status

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: number to check for transitions
  - type: bang
    description: resends bang according to current status

outlets:

  1st:
  - type: bang
    description: if a zero to non-0 transition is detected
  2nd:
  - type: bang
    description: if a non-0 to zero transition is detected

arguments:
  - type: float
    description: initial status value

methods:
  - type: change
    description: changes internal status



draft: false
---