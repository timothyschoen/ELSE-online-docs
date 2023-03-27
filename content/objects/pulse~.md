--- 


title: pulse~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz
  2nd:
  - type: float/signal
    description: pulse width (from 0 to 1)
  3rd:
  - type: float/signal
    description: phase sync (resets internal phase)
  4th:
  - type: float/signal
    description: phase offset (modulation input)

outlets:

  1st:
  - type: signal
    description: pulse signal

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: initial pulse width
  - type: float
    description: initial phase offset





draft: false
---