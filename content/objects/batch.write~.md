--- 


title: batch.write~

pdcategory: Buffers

inlets:

  1st:
  - type: bang
    description: record the whole array
  - type: signal
    description: signal inputs to record for each channel
  2nd:
  - type: signal
    description: signal inputs to record for each channel

outlets:

  1st:
  - type: bang
    description: outputs a bang when the object is done recording

arguments:
  - type: symbol
    description: array name to write to
  - type: float
    description: number of channels to record

methods:
  - type: set <symbol>
    description: sets array value



draft: false
---