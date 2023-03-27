--- 


title: midi.clock

pdcategory: MIDI

inlets:

  1st:
  - type: float
    description: sets BPM and also sets to internal clock

outlets:

  1st:
  - type: bang
    description: bang at each clock tick
  2nd:
  - type: float
    description: time interval in BPM from external source

arguments:
  - type: float
    description: sets BPM and also sets to internal clock

methods:
  - type: external
    description: sets to external clock



draft: false
---