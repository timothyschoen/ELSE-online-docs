--- 


title: args

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: output arguments list
  - type: anything
    description: sets new arguments

outlets:

  1st:
  - type: anything
    description: symbol, float or list, depending on the given arguments  or bang if no arguments are given to the parent patch (as in the help patch)

arguments:
  - type: symbol
    description: (optional) break character
  - type: float
    description: depth level





draft: false
---