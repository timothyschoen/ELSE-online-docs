--- 


title: beat~

pdcategory: Analysis

inlets:

  1st:
  - type: signal
    description: input to analyze

outlets:

  1st:
  - type: float
    description: detected bpm value

arguments:
  - type: float
    description: level threshold
  - type: float
    description: set window size
  - type: float
    description: set hop size

methods:
  - type: mode <float>
    description: set mode (0 to 8)
  - type: thresh <float>
    description: set threshold (0.1 to 1)
  - type: silence <float>
    description: set silence level in dBFS
  - type: window <float>
    description: set analysis window size in samples
  - type: hop <float>
    description: set hop size in samples

flags:
  - type: -mode <float>
    description: set mode (
  - type: -silence <float>
    description: set silence level (

draft: false
---