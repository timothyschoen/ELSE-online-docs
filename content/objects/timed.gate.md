--- 


title: timed.gate

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: float
    description: control trigger with the gate value
  - type: bang
    description: control trigger with the last/initial gate value
  2nd:
  - type: float
    description: gate time in ms

outlets:

  1st:
  - type: float
    description: timed gate

arguments:
  - type: float
    description: gate time in ms
  - type: float
    description: initial gate amplitude
  - type: float
    description: non-0 sets to retrigger mode

methods:
  - type: ms <float>
    description: gate time in ms
  - type: retrigger <float>
    description: non-0 sets to retrigger mode



draft: false
---