--- 


title: mono

pdcategory: MIDI

inlets:

  1st:
  - type: list
    description: MIDI note message (note, velocity)
  - type: float
    description: note values
  2nd:
  - type: float
    description: velocity values

outlets:

  1st:
  - type: float
    description: note values
  2nd:
  - type: float
    description: velocity values

arguments:
  - type: float
    description: non-0 sets to legato mode

methods:
  - type: mode <float>
    description: priority mode (0; last, 1; high, 2; low)
  - type: legato <float>
    description: non-0  legato mode, zero  restores default
  - type: flush
    description: sends a note off for the hanging note and clears memory
  - type: clear
    description: clears memory

flags:
  - type: -last
    description: sets mode to "last
  - type: -high
    description: sets mode to "high
  - type: -low
    description: sets mode to "low

draft: false
---