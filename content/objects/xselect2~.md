--- 


title: xselect2~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: signal
    description: selected channel with crossfade
  2nd:
  - type: signal
    description: secondary inputs are the channels to select from

outlets:

  1st:
  - type: signal
    description: crossfaded channels

arguments:
  - type: float
    description: number of channels (min 2, max 500)
  - type: float
    description: <1> — indexed mode,  <0> — non-indexed

methods:
  - type: index <float>
    description: <1>  indexed mode, <0>  non-indexed (default)



draft: false
---