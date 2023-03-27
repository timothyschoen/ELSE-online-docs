--- 


title: insert

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: outputs last message
  - type: anything
    description: message to have elements inserted into
  2nd:
  - type: anything
    description: elements to insert int a message
  3rd:
  - type: float
    description: index position to insert

outlets:

  1st:
  - type: anything
    description: output the resulting message

arguments:
  - type: float
    description: (optional) index
  - type: float
    description: message to insert





draft: false
---