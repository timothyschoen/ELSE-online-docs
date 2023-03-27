--- 


title: lag~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float/signal
    description: input signal
  2nd:
  - type: float/signal
    description: lag time in ms

outlets:

  1st:
  - type: signal
    description: lagged signal

arguments:
  - type: float
    description: lag time in ms

methods:
  - type: reset
    description: resets the filter



draft: false
---