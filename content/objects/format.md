--- 


title: format

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: outputs the formatted message
  - type: anything
    description: float/symbol atoms to format variables (messages with more than one item and sends the remaining items to the next inlets)

outlets:

  1st:
  - type: anything
    description: the formatted message

arguments:
  - type: anything
    description: atoms that may contain '%' variables (obligatory)





draft: false
---