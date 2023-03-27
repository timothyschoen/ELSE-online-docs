--- 


title: polymetro~

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: non-0 starts, zero stops
  - type: bang
    description: syncs/resets
  2nd:
  - type: float
    description: set tempo value in BPM
  3rd:
  - type: anything
    description: multiplier as a float or fraction (anything/symbol/float)

outlets:

  1st:
  - type: signal
    description: impulse base rhythm
  2nd:
  - type: signal
    description: impulse for relative rhythm

arguments:
  - type: float
    description: tempo in BPM
  - type: symbol/float
    description: polyrhythmic multiplier ratio





draft: false
---