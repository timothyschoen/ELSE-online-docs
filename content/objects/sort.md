--- 


title: sort

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: a message to sort
  - type: bang
    description: outputs the last incoming message sorted
  2nd:
  - type: float
    description: order (negative is descending, ascending otherwise)

outlets:

  1st:
  - type: list
    description: sorted list
  2nd:
  - type: list
    description: the sorted list as indexes of the original input

arguments:
  - type: float
    description: ascending if larger or equal than 0, descending otherwise





draft: false
---