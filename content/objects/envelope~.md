--- 


title: envelope~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float/signal
    description: phase input
  2nd:
  - type: float
    description: phase offset

outlets:

  1st:
  - type: signal
    description: envelope waveform

arguments:
  - type: anything
    description: sin, hann, tri, vsaw <float>, gauss <float>, trapezoid <float, float>

methods:
  - type: phase <float>
    description: phase offset (from 0 to 1)
  - type: anything
    description: set envelope type and arguments; <sin>, <hann>, <tri>, <vsaw, float>, <gauss float>, and <trap float float>

flags:
  - type: phase <float>
    description: phase offset (default 0)

draft: false
---