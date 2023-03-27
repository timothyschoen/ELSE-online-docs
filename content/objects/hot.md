--- 


title: hot

pdcategory: Data Management

inlets:

  1st:
  - type: bang
    description: outputs last stored values
  - type: anything
    description: any messages go to the corresponding outlet

outlets:

  1st:
  - type: anything
    description: messages from corresponding input

arguments:
  - type: float
    description: sets 'n' number of inlets/outlets (max 128)

methods:
  - type: set <anything>
    description: set any input message without output



draft: false
---