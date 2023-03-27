--- 


title: retune

pdcategory: Tuning

inlets:

  1st:
  - type: float
    description: MIDI pitch to retune
  2nd:
  - type: list
    description: scale in cents

outlets:

  1st:
  - type: list
    description: scale in cents

arguments:
  - type: list
    description: scale in cents

methods:
  - type: base <float>
    description: MIDI pitch base (decimals allowed)

flags:
  - type: -base <f>
    description: base MIDI pitch

draft: false
---