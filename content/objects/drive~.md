--- 


title: drive~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal input
  2nd:
  - type: signal/signal
    description: drive factor

outlets:

  1st:
  - type: signal
    description: the distorted signal

arguments:
  - type: float
    description: initial drive value (minimum 0)

methods:
  - type: mode <float>
    description: sets modes <0, 1, or 2>

flags:
  - type: -mode <float>
    description: sets distortion (0  default, 1, or 2)

draft: false
---