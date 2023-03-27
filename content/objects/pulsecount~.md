--- 


title: pulsecount~

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: signal
    description: trigger signal to count
  2nd:
  - type: signal
    description: an impulse resets counter to zero

outlets:

  1st:
  - type: signal
    description: the trigger count

arguments:
  - type: float
    description: maximum count value

methods:
  - type: max <float>
    description: sets maximum count value



draft: false
---