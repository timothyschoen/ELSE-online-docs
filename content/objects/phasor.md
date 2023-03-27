--- 


title: phasor

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: frequency in Hz
  2nd:
  - type: float
    description: phase sync (resets internal phase)

outlets:

  1st:
  - type: float
    description: phase" value from 0 to 127

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: initial phase offset

methods:
  - type: rate <float>
    description: rate period in ms

flags:
  - type: -rate <float>
    description: rate period in ms (default 1, min 0.1)

draft: false
---