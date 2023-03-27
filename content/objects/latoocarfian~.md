--- 


title: latoocarfian~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz (negative values accepted)
  - type: list
    description: 2 floats set x[n-1] and y[n-1], respectively

outlets:

  1st:
  - type: signal
    description: Latoocarfian chaotic signal

arguments:
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets a
  - type: float
    description: sets b
  - type: float
    description: sets c
  - type: float
    description: sets d
  - type: float
    description: sets initial value of y[n-1]
  - type: float
    description: sets initial value of x[n-1]

methods:
  - type: coeffs <f, f, f, f>
    description: list sets values of 'a', 'b', 'c' and 'd'



draft: false
---