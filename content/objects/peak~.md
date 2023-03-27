--- 


title: peak~

pdcategory: Analysis

inlets:

  1st:
  - type: signal
    description: signal to analyze

outlets:

  1st:
  - type: float
    description: peak amplitude value

arguments:
  - type: float
    description: analysis window size in samples
  - type: float
    description: hop size in samples

methods:
  - type: set <float, float>
    description: sets window and hop size in samples
  - type: db
    description: change peak value to dBFS
  - type: linear
    description: change peak value to linear (the default is linear)

flags:
  - type: -db
    description: sets the output to dBFS

draft: false
---