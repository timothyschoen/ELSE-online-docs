--- 


title: noisegate~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal to be gated
  2nd:
  - type: float
    description: threshold in dBFS

outlets:

  1st:
  - type: signal
    description: gated signal

arguments:
  - type: float
    description: threshold in dBFS
  - type: float
    description: attack/release time in ms



flags:
  - type: -size <float>
    description: sets analysis window size in samples (default 512)

draft: false
---