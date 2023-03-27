--- 


title: standard~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz (negative values accepted)
  - type: list
    description: 2 floats set x[n-1] and y[n-1], respectively

outlets:

  1st:
  - type: signal
    description: standard map chaotic signal

arguments:
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets k
  - type: float
    description: sets initial value of x[n-1]
  - type: float
    description: sets initial value of y[n-1]

methods:
  - type: k <float>
    description: sets the value of k



draft: false
---