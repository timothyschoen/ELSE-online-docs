--- 


title: group

pdcategory: Data Management

inlets:

  1st:
  - type: anything
    description: input messages to be regrouped
  - type: bang
    description: outputs the remainder
  2nd:
  - type: float
    description: calculate or output the last calculated value

outlets:

  1st:
  - type: anything
    description: the regrouped message
  2nd:
  - type: bang
    description: when there's no remainder (group is empty)

arguments:
  - type: float
    description: group size

methods:
  - type: clear
    description: clears the remainder

flags:
  - type: -trim
    description: trims selectors (list/symbol) on the output

draft: false
---