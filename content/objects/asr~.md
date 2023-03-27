--- 


title: asr~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float/signal
    description: gate values
  2nd:
  - type: float/signal
    description: attack time in ms
  3rd:
  - type: float/signal
    description: release time in ms

outlets:

  1st:
  - type: signal
    description: envelope signal
  2nd:
  - type: float
    description: envelope status (on=1 / off=0)

arguments:
  - type: float
    description: attack time in ms
  - type: float
    description: release time in  ms

methods:
  - type: lin <float>
    description:  non-0 sets to "lin" mode, "log" otherwise

flags:
  - type: -lin
    description: sets to linear mode (default=log)

draft: false
---