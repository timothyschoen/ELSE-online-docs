--- 


title: nmess

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: a message to be gated
  2nd:
  - type: bang
    description: resets and reopens gate
  - type: float
    description: resets and sets 'n' number of messages

outlets:

  1st:
  - type: anything
    description: output a message if the gate is opened
  2nd:
  - type: anything
    description: output a message if the gate is closed

arguments:
  - type: float
    description: sets 'n' number of messages





draft: false
---