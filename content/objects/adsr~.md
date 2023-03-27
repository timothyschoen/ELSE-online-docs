--- 


title: adsr~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: signal
    description: gate value
  - type: float
    description: gate value in MIDI velocity range (0-127 is 0-1)
  - type: bang
    description: trigger/retrigger
  2nd:
  - type: float/signal
    description: attack time in ms
  3rd:
  - type: float/signal
    description: decay time in ms
  4th:
  - type: float/signal
    description: sustain amplitude (ratio to gate value)
  5th:
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
    description: decay time in ms
  - type: float
    description: sustain amplitude (ratio to gate value)
  - type: float
    description: release time in ms

methods:
  - type: lin <float>
    description: non-0 sets to "lin" mode, "log" otherwise

flags:
  - type: -lin
    description: sets to linear mode (default=log)

draft: false
---