--- 


title: resonant~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered or excite the resonator
  2nd:
  - type: float/signal
    description: central frequency in Hz
  3rd:
  - type: signal
    description: resonance (t60 decay time in ms or Q)

outlets:

  1st:
  - type: signal
    description: methods;
  - type: clear
    description: clears filter's memory
  - type: bypass <float>
    description: 1 (bypass on), 0 (bypass off)
  - type: t60
    description: sets resonance parameter in decay time in ms (default)
  - type: q
    description: sets resonance parameter to Q

arguments:
  - type: float
    description: center frequency in Hz
  - type: float
    description: resonance





draft: false
---