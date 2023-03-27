--- 


title: fbsine2~

pdcategory: Signal Generators

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz (negative values accepted)
  - type: list
    description: 2 floats set x[n-1] and y[n-1] respectively

outlets:

  1st:
  - type: signal
    description: feedback sine chaotic signal

arguments:
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets 'im'
  - type: float
    description: sets 'fb'
  - type: float
    description: sets 'a'
  - type: float
    description: sets 'c'
  - type: float
    description: sets initial value of x[n]
  - type: float
    description: sets initial phase value of y[n]

methods:
  - type: coeffs <f, f, f, f>
    description: sets values of 'im', 'fb', 'a' and 'c', respectively
  - type: clear
    description: clears values of x[n-1] and y[n-1]



draft: false
---