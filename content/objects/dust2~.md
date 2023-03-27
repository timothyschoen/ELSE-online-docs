--- 


title: dust2~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: density (rate) of random impulses

outlets:

  1st:
  - type: signal
    description: random impulses

arguments:
  - type: float
    description: density

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: seed value (

draft: false
---