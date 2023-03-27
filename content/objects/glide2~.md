--- 


title: glide2~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: signal
    description: incoming signal to smooth out
  2nd:
  - type: float
    description: ramp-up time in ms
  3rd:
  - type: float
    description: ramp-down time in ms

outlets:

  1st:
  - type: signal
    description: smoothed out/filtered signal

arguments:
  - type: float
    description: ramp-up time in ms
  - type: float
    description: ramp-down time in ms

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