--- 


title: lfnoise~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: frequency input in Hz
  2nd:
  - type: signal
    description: impulse forces a new random value

outlets:

  1st:
  - type: signal
    description: impulse forces a new random value

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: interpolation 0 (off) or 1 (on)

methods:
  - type: interp <float>
    description: interpolation 0 (off, default) or 1 (on)
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: sets seed (

draft: false
---