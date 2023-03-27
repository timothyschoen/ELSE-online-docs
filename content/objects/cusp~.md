--- 


title: cusp~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz (negative values accepted)
  - type: list
    description: 3 floats sets 'a', 'b' and y[n-1]

outlets:

  1st:
  - type: signal
    description: cusp map chaotic signal

arguments:
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets 'a'
  - type: float
    description: sets 'b'
  - type: float
    description: sets initial value of y[n-1]





draft: false
---