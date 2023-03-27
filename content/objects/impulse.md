--- 


title: impulse

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
  - type: bang
    description: bang at period transitions

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