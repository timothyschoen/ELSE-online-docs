--- 


title: drunkard

pdcategory: Random and Noise

inlets:

  1st:
  - type: bang
    description: triggers a random output
  - type: float
    description: sets new current value and outputs it
  2nd:
  - type: float
    description: sets lower bound
  3rd:
  - type: float
    description: sets upper bound

outlets:

  1st:
  - type: float
    description: random number output as result of the random walk

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
  - type: set <float>
    description: sets the current value (without output)
  - type: p <float>
    description: sets probability of a positive step in %

flags:
  - type: -seed <float>
    description: 
  - type: -p <float>
    description: 

draft: false
---