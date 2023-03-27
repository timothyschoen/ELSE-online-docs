--- 


title: meter~

pdcategory: UI

inlets:

  1st:
  - type: signal
    description: incoming mono signal to be vu-metered

outlets:

  1st:
  - type: signal
    description: incoming signal is passed through
  2nd:
  - type: list
    description: vu values (RMS/peak amplitude in dBFS)

arguments:
  - type: float
    description: window size for the [vu~] object
  - type: float
    description: hop size for the [vu~] object





draft: false
---