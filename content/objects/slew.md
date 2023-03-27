--- 


title: slew

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float
    description: values to be slew limited
  2nd:
  - type: float
    description: speed limit

outlets:

  1st:
  - type: float
    description: slew limited values

arguments:
  - type: float
    description: slew limit speed
  - type: float
    description: initial start value

methods:
  - type: set <float>
    description: sets new start point and goes back to target
  - type: rate <float>
    description: refresh rate in ms

flags:
  - type: -rate <f>
    description: sets refresh rate in ms (default 5, minimum 1)

draft: false
---