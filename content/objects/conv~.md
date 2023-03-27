--- 


title: conv~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: input signal

outlets:

  1st:
  - type: signal
    description: output signal

arguments:
  - type: float
    description: optional  partition size
  - type: symbol
    description: file name to open as impulse response

methods:
  - type: size <float>
    description: sets partition size
  - type: load <symbol>
    description: loads IR sound file



draft: false
---