--- 


title: fbsine~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz
  2nd:
  - type: float/signal
    description: feedback value
  3rd:
  - type: float/signal
    description: phase sync (resets internal phase)
  4th:
  - type: float/signal
    description: phase offset (modulation input)

outlets:

  1st:
  - type: signal
    description: sine wave signal

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: initial feedback value
  - type: float
    description: initial phase offset
  - type: float
    description: mean filter; on <1> or off <0>

methods:
  - type: filter <float>
    description: turns mean filter on <1> or off <0>



draft: false
---