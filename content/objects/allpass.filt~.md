--- 


title: allpass.filt~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered
  2nd:
  - type: float/signal
    description: central frequency in Hz
  3rd:
  - type: float/signal
    description: filter resonance (Q)

outlets:

  1st:
  - type: signal
    description: filtered signal

arguments:
  - type: float
    description: order from 2 to 64
  - type: float
    description: frequency in Hz
  - type: float
    description: filter Q





draft: false
---