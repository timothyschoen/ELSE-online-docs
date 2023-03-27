--- 


title: xgate~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: signal
    description: input signal to route
  - type: float
    description: selected outlet (0 is none)

outlets:

  1st:
  - type: signal
    description: routed output
  2nd:
  - type: list
    description: reports output number and off status

arguments:
  - type: float
    description: number of outlets/channels (min 1, max 500)
  - type: float
    description: crossfade time in ms
  - type: float
    description: initially selected channel

methods:
  - type: time <float>
    description: crossfade time in ms



draft: false
---