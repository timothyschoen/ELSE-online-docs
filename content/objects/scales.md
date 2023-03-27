--- 


title: scales

pdcategory: Tuning

inlets:

  1st:
  - type: bang
    description: generates scale
  2nd:
  - type: float
    description: sets octave number

outlets:

  1st:
  - type: list
    description: scale as note names
  2nd:
  - type: list
    description: scale as MIDI pitches
  3rd:
  - type: list
    description: scale as cents

arguments:
  - type: float
    description: sets octave number to start from
  - type: list
    description: sets scale

methods:
  - type: anything <symbol, f>
    description: note name and its degree (optional, default 1)
  - type: list <f, symbol>
    description: degree start point and tonic
  - type: scale <list>
    description: sets scale



draft: false
---