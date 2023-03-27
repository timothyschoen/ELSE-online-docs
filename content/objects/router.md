--- 


title: router

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: message to send through a specified outlet
  2nd:
  - type: float
    description: sets outlet number (-1 is none)

outlets:

  1st:
  - type: anything
    description: outlets for routing any received message

arguments:
  - type: float
    description: number of outlets (2 to 512)
  - type: float
    description: sets initially open outlet





draft: false
---