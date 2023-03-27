--- 


title: rand.dist

pdcategory: Random and Noise

inlets:

  1st:
  - type: bang
    description: generates a random output
  - type: float
    description: range from 0-127) get quantile
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
  - type: symbol
    description: sets table name
  - type: float
    description: sets minimum output
  - type: float
    description: sets maximum output

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal
  - type: set <symbol>
    description: sets array name

flags:
  - type: -seed <float>
    description: seed value

draft: false
---