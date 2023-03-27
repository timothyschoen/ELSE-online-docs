--- 


title: lorenz~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz (negative values accepted)
  - type: list
    description: 3 floats set x[n-1], y[n-1] and z[n-1] respectively

outlets:

  1st:
  - type: signal
    description: Lorenz chaotic signal

arguments:
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets 's'
  - type: float
    description: sets 'r'
  - type: float
    description: sets 'b'
  - type: float
    description: sets 'h'
  - type: float
    description: sets initial value of x[n-1]
  - type: float
    description: sets initial value of y[n-1]
  - type: float
    description: sets initial value of z[n-1]

methods:
  - type: coeffs <f,f,f,f>
    description: list sets values of 's', 'r', 'b' and 'h'
  - type: clear
    description: clears values of z, y and z



draft: false
---