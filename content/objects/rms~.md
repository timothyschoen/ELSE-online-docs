--- 


title: rms~

pdcategory: Analysis

inlets:

  1st:
  - type: signal
    description: the signal to analyze
  - type: set <f,f>
    description: sets window and hop size in samples
  - type: db
    description: change RMS value to dBFS
  - type: linear
    description: change RMS value to linear

outlets:

  1st:
  - type: float
    description: RMS value

arguments:
  - type: float
    description: analysis window size in samples
  - type: float
    description: hop size in samples





draft: false
---