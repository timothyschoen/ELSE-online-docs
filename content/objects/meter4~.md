--- 


title: meter4~

pdcategory: UI

inlets:

  1st:
  - type: signal
    description: incoming signal channels to be vu-metered

outlets:

  1st:
  - type: signal
    description: incoming signals are passed through
  2nd:
  - type: list
    description: vu values (RMS/peak amplitude in dBFS) of inputs

arguments:
  - type: float
    description: window size for the [vu~] objects
  - type: float
    description: hop size for the [vu~] objects





draft: false
---