--- 


title: lfnoise

pdcategory: Random and Noise

inlets:

  1st:
  - type: float
    description: frequency in Hz up to 100 (negative values accepted)
  2nd:
  - type: bang
    description: reset to a new random value

outlets:

  1st:
  - type: float
    description: low frequency noise output in the range from 0  127

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: interpolation off (0) or on (1)

methods:
  - type: interp <float>
    description: non-0 sets to linear interpolation
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: sets seed (

draft: false
---