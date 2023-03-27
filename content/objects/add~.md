--- 


title: add~

pdcategory: Signal Math

inlets:

  1st:
  - type: float/signal
    description: value to accumulate
  - type: bang
    description: resets sum to starting point
  2nd:
  - type: signal
    description: impulse resets to starting point

outlets:

  1st:
  - type: signal
    description: the accumulated value

arguments:
  - type: float
    description: starting sum

methods:
  - type: set <float>
    description: sets starting sum



draft: false
---