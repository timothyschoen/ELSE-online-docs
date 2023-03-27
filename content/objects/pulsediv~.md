--- 


title: pulsediv~

pdcategory: Signal Generators

inlets:

  1st:
  - type: signal
    description: trigger signal to be divided
  2nd:
  - type: signal
    description: an impulse resets the counter to the start value

outlets:

  1st:
  - type: signal
    description: divided triggers (impulse)
  2nd:
  - type: signal
    description: impulse for the other trigger inputs

arguments:
  - type: float
    description: divide value
  - type: float
    description: start count value





draft: false
---