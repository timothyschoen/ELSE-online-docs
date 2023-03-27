--- 


title: xselect~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: float
    description: selected input (0 is none)
  2nd:
  - type: signal
    description: inputs to select from

outlets:

  1st:
  - type: signal
    description: selected inlet/channel
  2nd:
  - type: list
    description: reports input number and off status

arguments:
  - type: float
    description: number of inputs
  - type: float
    description: crossfade time in ms
  - type: float
    description: initially selected channel

methods:
  - type: time <float>
    description: crossfade time in ms



draft: false
---