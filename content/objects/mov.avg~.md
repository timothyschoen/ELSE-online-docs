--- 


title: mov.avg~

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
    description: the moving average over the last 'n' samples

arguments:
  - type: float
    description: sets initial number of samples

methods:
  - type: clear
    description: clears filter's memory
  - type: size <float>
    description: sets new maximum size and clears filter's memory

flags:
  - type: -size <float>
    description: sets buffer size
  - type: -abs
    description: sets to absolute average mode

draft: false
---