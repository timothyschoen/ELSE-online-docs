--- 


title: ramp~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: signal
    description: signal trigger (starts ramp from the reset point value)
  - type: bang
    description: control rate trigger (starts ramp from the reset point value)
  2nd:
  - type: float/signal
    description: sets the increment value
  3rd:
  - type: float/signal
    description: sets the minimum value
  4th:
  - type: float/signal
    description: sets the maximum value

outlets:

  1st:
  - type: signal
    description: the ramp signal
  2nd:
  - type: bang
    description: a bang when ramp is finished

arguments:
  - type: float
    description: increment value
  - type: float
    description: minimum value
  - type: float
    description: maximum value
  - type: float
    description: start/reset value

methods:
  - type: mode <float>
    description: 0  wrap, 1  clip, 2  reset
  - type: off
    description: prevents the ramp from automatically starting

flags:
  - type: -set <float>
    description: sets the reset point value
  - type: -mode <float>
    description: 0  wrap, 1  clip, 2  reset
  - type: -stop
    description: stops incrementing
  - type: -start
    description: (re)starts incrementing
  - type: -reset
    description: stops and goes back to the reset point

draft: false
---