--- 


title: randpulse~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz
  2nd:
  - type: float/signal
    description: pulse width (0-1)
  3rd:
  - type: float/signal
    description: phase sync (internal phase reset)

outlets:

  1st:
  - type: signal
    description: random pulse signal

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: initial pulse width

methods:
  - type: seed <float>
    description:  non-0 sets to random gate value mode

flags:
  - type: -seed <float>
    description: seed value

draft: false
---