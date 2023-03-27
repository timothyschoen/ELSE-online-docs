--- 


title: perlin~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz

outlets:

  1st:
  - type: signal
    description: Perlin noise signal

arguments:
  - type: float
    description: sets frequency in Hz

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: sets seed (

draft: false
---