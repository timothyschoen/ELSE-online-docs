--- 


title: meter2~

pdcategory: UI

inlets:

  1st:
  - type: signal
    description: left incoming signal channels to be vu-metered
  2nd:
  - type: signal
    description: right incoming signal channels to be vu-metered

outlets:

  1st:
  - type: signal
    description: left incoming signals are passed through
  2nd:
  - type: signal
    description: right incoming signals are passed through
  3rd:
  - type: list
    description: vu values (RMS/peak amplitude in dBFS) of inputs

arguments:
  - type: float
    description: window size for the [vu~] objects
  - type: float
    description: hop size for the [vu~] objects





draft: false
---