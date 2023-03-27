--- 


title: stepnoise~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: frequency input in Hz

outlets:

  1st:
  - type: signal
    description: bandlimited step noise

arguments:
  - type: float
    description: frequency in Hz

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: sets seed

draft: false
---