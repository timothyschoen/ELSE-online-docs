--- 


title: stretch.shift~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: audio signal input
  - type: bang
    description: resets to the beginning of the delay line
  2nd:
  - type: float
    description: sets grain size
  3rd:
  - type: float
    description: sets speed
  4th:
  - type: float
    description: sets transposition in cents

outlets:

  1st:
  - type: signal
    description: the buffer signal of the corresponding channel

arguments:
  - type: float
    description: sets buffer size in ms
  - type: float
    description: sets playing speed
  - type: float
    description: sets transposition in cents
  - type: float
    description: sets grain size in ms

methods:
  - type: size <float>
    description: sets buffer size in ms



draft: false
---