--- 


title: panic

pdcategory: MIDI

inlets:

  1st:
  - type: bang
    description: sends note off for hanging notes
  - type: float
    description: raw MIDI data stream

outlets:

  1st:
  - type: float
    description: raw MIDI data stream



methods:
  - type: clear
    description: clears the hanging notes that [midiflush] keeps track of



draft: false
---