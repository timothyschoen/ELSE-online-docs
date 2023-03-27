--- 


title: batch.rec~

pdcategory: Buffers

inlets:

  1st:
  - type: signal
    description: signal inputs to record for each channel

outlets:

  1st:
  - type: bang
    description: outputs a bang when the object is done recording

arguments:
  - type: symbol
    description: (optional) file name to save to
  - type: symbol
    description: number of channels to record

methods:
  - type: rec <float>
    description: starts recording for given amount of time in ms. If no float is given, the last set value is used
  - type: set <symbol>
    description: sets file name (no symbol opens dialog box)



draft: false
---