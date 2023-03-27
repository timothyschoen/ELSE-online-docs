--- 


title: dollsym

pdcategory: Data Management

inlets:

  1st:
  - type: symbol
    description: a symbol to be expanded if it contains dollar args
  - type: anything
    description: a one element symbol is also expanded
  - type: bang
    description: output expanded dollar symbol

outlets:

  1st:
  - type: symbol
    description: the expanded symbol

arguments:
  - type: float
    description: (optional) depth
  - type: symbol
    description: symbol to be expanded





draft: false
---