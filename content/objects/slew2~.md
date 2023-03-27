--- 


title: slew2~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float/signal
    description: values to be slew limited
  2nd:
  - type: float/signal
    description: speed limit upwards
  3rd:
  - type: float
    description: speed limit downwards

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



draft: false
---