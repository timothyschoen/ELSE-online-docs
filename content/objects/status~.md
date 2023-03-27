--- 


title: status~

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: signal
    description: signal to detect transitions from

outlets:

  1st:
  - type: signal
    description: impulse if a zero to non-0 transition is detected
  2nd:
  - type: signal
    description: impulse if a non-0 to zero transition is detected

arguments:
  - type: float
    description: initial status value





draft: false
---