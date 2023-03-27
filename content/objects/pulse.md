--- 


title: pulse

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: frequency in Hz
  2nd:
  - type: float
    description: pulse width (from 0 to 1)
  3rd:
  - type: float
    description: phase sync (resets internal phase)

outlets:

  1st:
  - type: float
    description: toggle output

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: pulse width
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