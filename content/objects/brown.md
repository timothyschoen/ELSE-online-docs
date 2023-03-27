--- 


title: brown

pdcategory: Random and Noise

inlets:

  1st:
  - type: bang
    description: generate new random step
  - type: float
    description: sets maximum random step (from 0 to 1)

outlets:

  1st:
  - type: float
    description: random value based on brownian motion

arguments:
  - type: float
    description: maximum step

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: sets seed (

draft: false
---