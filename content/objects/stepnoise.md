--- 


title: stepnoise

pdcategory: Random and Noise

inlets:

  1st:
  - type: float
    description: frequency in Hz up to 100 (negative values accepted)

outlets:

  1st:
  - type: float
    description: Step noise in the range from 0  127

arguments:
  - type: float
    description: frequency in Hz

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <f>
    description: sets seed (

draft: false
---