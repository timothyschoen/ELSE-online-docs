--- 


title: vu~

pdcategory: Analysis

inlets:

  1st:
  - type: float
    description: signal to analyze

outlets:

  1st:
  - type: float
    description: RMS amplitude value in dBFs
  2nd:
  - type: float
    description: peak amplitude value in dBFS

arguments:
  - type: float
    description: analyses window size in samples
  - type: float
    description: hop size in samples

methods:
  - type: set <f,f>
    description: sets window and hop size in samples



draft: false
---