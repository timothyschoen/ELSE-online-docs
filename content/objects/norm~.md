--- 


title: norm~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal to be normalized
  2nd:
  - type: float
    description: normalize level in dBFS

outlets:

  1st:
  - type: signal
    description: normalized signal

arguments:
  - type: float
    description: normalize level in dBFS



flags:
  - type: -size <float>
    description: sets analysis window size in samples (default 1024)

draft: false
---