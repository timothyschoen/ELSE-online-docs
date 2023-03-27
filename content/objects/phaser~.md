--- 


title: phaser~

pdcategory: Effects

inlets:

  1st:
  - type: signal
    description: input to phaser
  2nd:
  - type: signal
    description: frequency

outlets:

  1st:
  - type: signal
    description: phaser output

arguments:
  - type: float
    description: number of stages from 2 to 64
  - type: float
    description: q resonance
  - type: float
    description: dry/wet ratio from 0-1

methods:
  - type: q <float>
    description: internal allpass resonance
  - type: wet <float>
    description: dry/wet ratio from 0-1



draft: false
---