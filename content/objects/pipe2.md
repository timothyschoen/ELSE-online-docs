--- 


title: pipe2

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: message to be delayed
  2nd:
  - type: float
    description: sets delay time in ms

outlets:

  1st:
  - type: anything
    description: the delayed message

arguments:
  - type: float
    description: delay time in ms

methods:
  - type: clear
    description: clears the delay time
  - type: flush
    description: outputs all stored elements



draft: false
---