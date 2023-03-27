--- 


title: polymetro

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: non-0 starts, zero stops
  - type: bang
    description: syncs (restarts count) when polymetro is on
  2nd:
  - type: float
    description: set tempo value in BPM
  3rd:
  - type: anything
    description: multiplier as a float or fraction (anything/symbol)

outlets:

  1st:
  - type: float
    description: count for base rhythm
  2nd:
  - type: float
    description: count for relative rhythm

arguments:
  - type: float
    description: tempo in BPM
  - type: symbol/float
    description: polyrhythmic multiplier ratio

methods:
  - type: tempo <float>
    description: set tempo value in BPM

flags:
  - type: -b
    description: sets to bang mode output (instead of floats)

draft: false
---