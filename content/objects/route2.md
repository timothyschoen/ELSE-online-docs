--- 


title: route2

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: any message to be routed according to its 1st element

outlets:

  1st:
  - type: list
    description: rest of message that corresponds to an argument
  2nd:
  - type: list
    description: input message if no match was found

arguments:
  - type: float/symbol
    description: list of addresses to route to





draft: false
---