--- 


title: glide2

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float
    description: input signal
  2nd:
  - type: float
    description: glide up time in ms
  3rd:
  - type: float
    description: glide down time in ms

outlets:

  1st:
  - type: signal
    description: glided signal

arguments:
  - type: list
    description: glide up and down time in ms

methods:
  - type: reset
    description: resets glide to input value
  - type: exp <float>
    description: sets exponential factor
  - type: rate <float>
    description: refresh rate in ms

flags:
  - type: -exp <float>
    description: sets exponential factor (default 1  linear)
  - type: -rate <float>
    description: sets refresh rate in ms (default 5, minimum 1)

draft: false
---