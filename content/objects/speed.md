--- 


title: speed

pdcategory: Envelopes and LFOs

inlets:

  1st:
  - type: float
    description: set bpm immediately
  - type: list
    description: <f,f> — target, number of beats; <f,f,f> — start, target, number of beats

outlets:

  1st:
  - type: float
    description: bpm change
  2nd:
  - type: float
    description: total time in ms

arguments:
  - type: float
    description: initial bpm

methods:
  - type: set <list>
    description: floats/lists precede by 'set' waits for a bang to trigger
  - type: bang
    description: triggers the object after a 'set' message



draft: false
---