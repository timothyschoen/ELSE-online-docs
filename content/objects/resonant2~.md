--- 


title: resonant2~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered or excite the resonator
  2nd:
  - type: float/signal
    description: central frequency in Hz
  3rd:
  - type: float/signal
    description: attack time in ms
  4th:
  - type: float/signal
    description: decay time in ms

outlets:

  1st:
  - type: signal
    description: resonator/filtered signal

arguments:
  - type: float
    description: center frequency in Hz
  - type: float
    description: attack time in ms
  - type: float
    description: decay time in ms

methods:
  - type: clear
    description: clears filter's memory



draft: false
---