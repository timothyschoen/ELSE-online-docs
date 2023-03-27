--- 


title: slew~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float/signal
    description: values to be slew limited
  2nd:
  - type: float
    description: speed limit

outlets:

  1st:
  - type: signal
    description: slew limited values

arguments:
  - type: float
    description: slew limit speed

methods:
  - type: set <float>
    description: sets new start point and goes back to target



draft: false
---