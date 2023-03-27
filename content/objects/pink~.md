--- 


title: pink~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float
    description: set number of octaves (minimum 1, max 31)

outlets:

  1st:
  - type: signal
    description: pink noise

arguments:
  - type: float
    description: number of octaves

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: sets seed (

draft: false
---