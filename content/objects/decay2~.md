--- 


title: decay2~

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float
    description: control trigger
  - type: bang
    description: control trigger
  - type: signal
    description: impulse trigger
  2nd:
  - type: float/signal
    description: attack time in ms
  3rd:
  - type: float/signal
    description: decay time in ms

outlets:

  1st:
  - type: signal
    description: decayed signal

arguments:
  - type: float
    description: attack in ms
  - type: float
    description: decay in ms

methods:
  - type: clear
    description: clears filter's memory



draft: false
---