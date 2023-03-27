--- 


title: slew2

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float
    description: values to be slew limited
  2nd:
  - type: float
    description: up slew speed limit
  3rd:
  - type: float
    description: down slew speed limit

outlets:

  1st:
  - type: float
    description: slew limited values

arguments:
  - type: float
    description: up slew limit speed
  - type: float
    description: down slew limit speed

methods:
  - type: set <float>
    description: sets new start point and goes back to target
  - type: rate <float>
    description: refresh rate in ms

flags:
  - type: -rate <float>
    description: sets refresh rate in ms (default 5, minimum 1)

draft: false
---