--- 


title: drunkard~

pdcategory: Random and Noise

inlets:

  1st:
  - type: signal
    description: impulses triggers a random output
  - type: list
    description: two floats set lower and upper bound
  2nd:
  - type: float
    description: sets lower bound
  3rd:
  - type: float
    description: sets upper bound

outlets:

  1st:
  - type: signal
    description: random value as result of the random walk

arguments:
  - type: float
    description: sets step range
  - type: float
    description: sets minimum value
  - type: float
    description: sets maximum value

methods:
  - type: step <float>
    description: sets step range
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal
  - type: p <float>
    description: sets probability of a positive step in %

flags:
  - type: -seed <float>
    description: sets seed (
  - type: -p <float>
    description: sets probability (default 70)

draft: false
---