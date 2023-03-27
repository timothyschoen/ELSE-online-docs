--- 


title: pimp

pdcategory: Signal Generators

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
  2nd:
  - type: bang
    description: output a bang at period transitions

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
    description: rate period in ms

draft: false
---