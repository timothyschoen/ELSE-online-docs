--- 


title: lag2~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float/signal
    description: input signal
  2nd:
  - type: float/signal
    description: lag uptime in ms
  3rd:
  - type: float/signal
    description: lag downtime in ms

outlets:

  1st:
  - type: signal
    description: lagged signal

arguments:
  - type: float
    description: lag uptime in ms
  - type: float
    description: lag downtime in ms

methods:
  - type: reset
    description: resets the filter



draft: false
---