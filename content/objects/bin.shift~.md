--- 


title: bin.shift~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: the signal to be shifted
  2nd:
  - type: float
    description: sets number of bins to shift

outlets:

  1st:
  - type: signal
    description: the bin shifted signal

arguments:
  - type: float
    description: sets shift number
  - type: float
    description: non-0 sets to wrap mode

methods:
  - type: wrap <float>
    description: non-0 sets to wrap mode



draft: false
---