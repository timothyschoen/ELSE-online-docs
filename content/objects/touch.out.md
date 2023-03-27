--- 


title: touch.out

pdcategory: MIDI

inlets:

  1st:
  - type: float
    description: MIDI aftertouch
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
  - type: -poly
    description: sets the object to output polyphonic aftertouch

draft: false
---