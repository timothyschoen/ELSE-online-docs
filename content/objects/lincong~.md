--- 


title: lincong~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz (negative values accepted)
  - type: list
    description: 4 floats sets 'a', 'c', 'm' and y[n-1]

outlets:

  1st:
  - type: signal
    description: linear congruential chaotic signal

arguments:
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets 'a'
  - type: float
    description: sets 'c'
  - type: float
    description: sets 'm'
  - type: float
    description: sets initial value of y[n-1]





draft: false
---