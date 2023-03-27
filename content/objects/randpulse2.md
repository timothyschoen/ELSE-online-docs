--- 


title: randpulse2

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: 

outlets:

  1st:
  - type: signal
    description: random pulse signal

arguments:
  - type: float
    description: density
  - type: float
    description: non-0 sets to random gate value mode

methods:
  - type: rand <float>
    description: non-0 sets to random gate value mode
  - type: seed <float>
    description:  a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: sets seed

draft: false
---