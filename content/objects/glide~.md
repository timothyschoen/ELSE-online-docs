--- 


title: glide~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float/signal
    description: input signal
  2nd:
  - type: float/signal
    description: glide time in ms

outlets:

  1st:
  - type: signal
    description: glided signal

arguments:
  - type: float
    description: glide time in ms

methods:
  - type: reset
    description: resets glide to input value
  - type: exp <float>
    description: sets exponential factor

flags:
  - type: -exp <float>
    description: sets exponential factor (default 1  linear)

draft: false
---