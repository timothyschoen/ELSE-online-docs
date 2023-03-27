--- 


title: mtx~

pdcategory: Mixing and Routing

inlets:

  1st:
  - type: list
    description: inlet, outlet, non-0  on, 0  off
  2nd:
  - type: signal
    description: signals to route/mix

outlets:

  1st:
  - type: signal
    description: routed signals
  2nd:
  - type: list
    description: all connections list dump message

arguments:
  - type: float
    description: number of inputs
  - type: float
    description: number of outputs
  - type: float
    description: fade time in ms

methods:
  - type: fade <float>
    description: sets fade time in ms
  - type: dump
    description: outputs state of all cells
  - type: clear
    description: clears all connections



draft: false
---