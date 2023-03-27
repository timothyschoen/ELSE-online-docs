--- 


title: midi.learn

pdcategory: MIDI

inlets:

  1st:
  - type: bang
    description: activate MIDI learn

outlets:

  1st:
  - type: list
    description: MIDI from learned input
  2nd:
  - type: anything
    description: learned controller

arguments:
  - type: symbol
    description: send name

methods:
  - type: query
    description: print send stored input on right outlet
  - type: forget
    description: forget input
  - type: set <symbol>
    description: set send name
  - type: teach <anything>
    description: teach a specific MIDI message



draft: false
---