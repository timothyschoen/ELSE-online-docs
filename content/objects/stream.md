--- 


title: stream

pdcategory: Data Management

inlets:

  1st:
  - type: float
    description: input stream of numbers
  - type: bang
    description: resends the last output list
  2nd:
  - type: float
    description: N group size

outlets:

  1st:
  - type: anything
    description: the regrouped message

arguments:
  - type: float
    description: N group size

methods:
  - type: clear
    description: clears the list



draft: false
---