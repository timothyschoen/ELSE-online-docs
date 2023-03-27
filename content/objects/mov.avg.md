--- 


title: mov.avg

pdcategory: Analysis

inlets:

  1st:
  - type: float
    description: value into the moving average
  2nd:
  - type: float
    description: sets new number of values and clears

outlets:

  1st:
  - type: float
    description: the moving average

arguments:
  - type: float
    description: sets initial values

methods:
  - type: clear
    description: clears all received values



draft: false
---