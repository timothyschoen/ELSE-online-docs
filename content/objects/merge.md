--- 


title: merge

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: any message type to merge
  - type: bang
    description: outputs last composed message

outlets:

  1st:
  - type: list
    description: message composed of the merged messages

arguments:
  - type: float
    description: number of inlets



flags:
  - type: -trim
    description: trims list selector

draft: false
---