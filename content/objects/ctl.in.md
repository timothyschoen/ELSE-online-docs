--- 


title: ctl.in

pdcategory: MIDI

inlets:

  1st:
  - type: float
    description: raw MIDI data stream
  2nd:
  - type: float
    description: Controller number
  3rd:
  - type: float
    description: MIDI channel (0 for omni)

outlets:

  1st:
  - type: float
    description: control value
  2nd:
  - type: float
    description: control number
  3rd:
  - type: float
    description: MIDI channel

arguments:
  - type: list
    description: one value sets channel number. Two values set control number





draft: false
---