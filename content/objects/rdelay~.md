--- 


title: rdelay~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal input into the delay line

outlets:

  1st:
  - type: signal
    description: the feed forward delayed signal

arguments:
  - type: float
    description: initial length

methods:
  - type: resize <float>
    description: changes the delay size
  - type: clear
    description: clears the delay buffer



draft: false
---