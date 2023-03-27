--- 


title: bend.in

pdcategory: MIDI

inlets:

  1st:
  - type: float
    description: raw MIDI data stream
  2nd:
  - type: float
    description: MIDI channel

outlets:

  1st:
  - type: float
    description: MIDI pitch bend value (from -1 to 1)
  2nd:
  - type: float
    description: MIDI channel

arguments:
  - type: float
    description: sets channel number



flags:
  - type: -raw
    description: sets to raw output mode (0-16383)

draft: false
---