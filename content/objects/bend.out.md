--- 


title: bend.out

pdcategory: MIDI

inlets:

  1st:
  - type: float
    description: pitch bend values
  2nd:
  - type: float
    description: MIDI channel

outlets:

  1st:
  - type: float
    description: raw MIDI stream

arguments:
  - type: float
    description: sets channel number



flags:
  - type: -raw
    description: sets to raw input mode (0-16383)

draft: false
---