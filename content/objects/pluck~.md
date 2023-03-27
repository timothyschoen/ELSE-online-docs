--- 


title: pluck~

pdcategory: Signal Generators

inlets:

  1st:
  - type: signal
    description: trigger (determines the amplitude)
  - type: float
    description: non-0 triggers and sets amplitude
  - type: bang
    description: triggers with last control amplitude (default 1)
  2nd:
  - type: float/signal
    description: frequency in Hz (minimum 1)
  3rd:
  - type: float/signal
    description: decay time in ms
  4th:
  - type: float/signal
    description: filter cutoff frequency
  5th:
  - type: float/signal
    description: optional noise input (with the -in flag)

outlets:

  1st:
  - type: signal
    description: the Karplus-Strong output

arguments:
  - type: float
    description: frequency in Hz
  - type: float
    description: decay time in ms
  - type: float
    description: filter cutoff frequency



flags:
  - type: -in
    description: creates an extra right inlet for noise input

draft: false
---