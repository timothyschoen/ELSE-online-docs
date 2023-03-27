--- 


title: xfade~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: signal
    description: left 'n' inlets are channels of input A. middle 'n' inlets are channels of input B
  2nd:
  - type: float/signal
    description: mix value from -1 (A) to 1 (B)

outlets:

  1st:
  - type: signal
    description: crossfaded output(s)

arguments:
  - type: float
    description: number of 'n' channels for each source
  - type: float
    description: initial mix value





draft: false
---