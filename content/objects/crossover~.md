--- 


title: crossover~

pdcategory: Filters

inlets:

  1st:
  - type: signal
    description: signal to be filtered
  2nd:
  - type: float/signal
    description: cutoff frequency

outlets:

  1st:
  - type: signal
    description: lowpass output
  2nd:
  - type: signal
    description: highpass output

arguments:
  - type: float
    description: cutoff frequency

methods:
  - type: clear
    description: clears filter's memory



draft: false
---