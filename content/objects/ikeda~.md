--- 


title: ikeda~

pdcategory: Random and Noise

inlets:

  1st:
  - type: float/signal
    description: frequency in Hz (negative values accepted)

outlets:

  1st:
  - type: signal
    description: y1[n]; Ikeda map chaotic signal 1st output
  2nd:
  - type: signal
    description: y2[n]; Ikeda map chaotic signal 2nd output

arguments:
  - type: float
    description: sets frequency in Hz
  - type: float
    description: sets initial "u" parameter
  - type: float
    description: sets initial value of y1[n-1]
  - type: float
    description: sets initial value of y2[n-1]

methods:
  - type: u <float>
    description: sets the value of u
  - type: list
    description: 2 floats set y1[n-1] and y2[n-1], respectively
  - type: clear
    description: clears previous outputs



draft: false
---