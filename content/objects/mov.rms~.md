--- 


title: mov.rms~

pdcategory: Analysis

inlets:

  1st:
  - type: signal
    description: the signal to be averaged
  2nd:
  - type: float/signal
    description: number of last samples to apply the average to

outlets:

  1st:
  - type: signal
    description: the RMS over the time window

arguments:
  - type: float
    description: sets number of samples in the window

methods:
  - type: clear
    description: clears buffer's memory
  - type: size <float>
    description: sets new maximum size and clears buffer's memory

flags:
  - type: -size <float>
    description: sets buffer size
  - type: -db
    description: sets output in dBFS

draft: false
---