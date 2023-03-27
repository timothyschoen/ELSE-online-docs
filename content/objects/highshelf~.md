--- 


title: highshelf~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered
  2nd:
  - type: float/signal
    description: shelving frequency in Hz
  3rd:
  - type: float/signal
    description: slope (from 0 to 1)
  4th:
  - type: float/signal
    description: gain in dB

outlets:

  1st:
  - type: signal
    description: filtered signal

arguments:
  - type: float
    description: shelving frequency in Hz
  - type: float
    description: slope from 0 to 1
  - type: float
    description: gain in dB

methods:
  - type: clear
    description: clears filter's memory if you blow it up
  - type: bypass <float>
    description: 1 (bypasses input signal) or 0 (doesn't bypass)



draft: false
---