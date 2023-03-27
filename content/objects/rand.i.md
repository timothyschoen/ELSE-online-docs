--- 


title: rand.i

pdcategory: Random and Noise

inlets:

  1st:
  - type: bang
    description: generate random number
  2nd:
  - type: float
    description: lowest random value
  3rd:
  - type: float
    description: highest random value

outlets:

  1st:
  - type: float
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