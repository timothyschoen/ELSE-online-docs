--- 


title: xgate2~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: signal
    description: channel selection
  2nd:
  - type: signal
    description: input channel to be routed

outlets:

  1st:
  - type: signal
    description: routed outputs with crossfade

arguments:
  - type: float
    description: number of output channels (min 2, max 500)
  - type: float
    description: <1> sets to indexed mode <0> sets to non-indexed

methods:
  - type: index <float>
    description: <1> — indexed mode, <0> — non-indexed (default)



draft: false
---