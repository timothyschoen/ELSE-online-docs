--- 


title: noteinfo

pdcategory: MIDI

inlets:

  1st:
  - type: float
    description: midi pitch
  - type: bang
    description: resets by sending note-offs and erasing events' memory
  2nd:
  - type: float
    description: note velocity

outlets:

  1st:
  - type: float
    description: voice number (from 0), event number, pitch, velocity, duration (delta time for note on and duration for note off)
  2nd:
  - type: float
    description: number of active voices







draft: false
---