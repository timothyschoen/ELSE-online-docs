--- 


title: routetype

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: any message to be routed according to its type

outlets:

  1st:
  - type: anything
    description: any message that corresponds to a type
  2nd:
  - type: anything
    description: non-corresponding messages if less than the 6 types are given

arguments:
  - type: anything
    description: list of types to route; no args — everything is sent to the outlet





draft: false
---