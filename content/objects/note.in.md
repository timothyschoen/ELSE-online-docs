--- 


title: note.in

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
    description: MIDI pitch
  2nd:
  - type: float
    description: MIDI velocity
  3rd:
  - type: float
    description: Note on/off flag (if -rel flag is given)
  4th:
  - type: float
    description: Rightmost outlet is MIDI channel

arguments:
  - type: float
    description: sets channel number



flags:
  - type: -rel
    description: sets the object to output release velocity and note on/off flag

draft: false
---