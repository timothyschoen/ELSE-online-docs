--- 


title: note.out

pdcategory: MIDI

inlets:

  1st:
  - type: float
    description: pitch values
  2nd:
  - type: float
    description: velocity values
  3rd:
  - type: float
    description: note on/off flag (if -rel flag is given)

outlets:

  1st:
  - type: float
    description: rightmost inlet is MIDI channel

arguments:
  - type: float
    description: sets channel number



flags:
  - type: -rel
    description: sets the object to output release velocity and note on/off flag

draft: false
---