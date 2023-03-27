--- 


title: henon~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz (negative values accepted)
  - type: list
    description: 2 floats set y[n-1] and y[n-2], respectively

outlets:

  1st:
  - type: signal
    description: Henon map chaotic signal

arguments:
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets a
  - type: float
    description: sets b
  - type: float
    description: sets initial value of y[n-1]
  - type: float
    description: sets initial value of y[n-2]

methods:
  - type: coeffs <f, f>
    description: floats set 'a' and 'b', respectively



draft: false
---