--- 


title: combine

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: message to be combined with another input close in time
  2nd:
  - type: float
    description: time interval for combining items to a list

outlets:

  1st:
  - type: anything
    description: combined (or not) messages

arguments:
  - type: float
    description: initial time in ms





draft: false
---