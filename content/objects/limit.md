--- 


title: limit

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: any message input message to be speed limited
  2nd:
  - type: float
    description: changes the time limit (in ms)

outlets:

  1st:
  - type: anything
    description: the last input in the time interval after last output
  2nd:
  - type: anything
    description: ignored messages (in ignore mode)

arguments:
  - type: float
    description: initial time limit
  - type: float
    description: non-0 sets to ignore mode





draft: false
---