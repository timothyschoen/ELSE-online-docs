--- 


title: freq.shift~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: signal to be shifted in frequency
  2nd:
  - type: float/signal
    description: the frequency shift value

outlets:

  1st:
  - type: signal
    description: frequency shifted signal
  2nd:
  - type: signal
    description: signal shifted in the opposite direction

arguments:
  - type: float
    description: the frequency shift value in Hz

methods:
  - type: clear
    description: clears filter's memory



draft: false
---