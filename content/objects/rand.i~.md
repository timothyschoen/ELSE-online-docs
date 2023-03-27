--- 


title: rand.i~

pdcategory: Random and Noise

inlets:

  1st:
  - type: signal
    description: trigger signal
  - type: bang
    description: control rate trigger
  2nd:
  - type: float/signal
    description: lowest random value
  3rd:
  - type: float/signal
    description: highest random value

outlets:

  1st:
  - type: signal
    description: random values

arguments:
  - type: float
    description: minimum
  - type: float
    description: maximum

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: seed value

draft: false
---