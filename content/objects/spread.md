--- 


title: spread

pdcategory: Data Management

inlets:

  1st:
  - type: float
    description: input value to spread

outlets:

  1st:
  - type: float
    description: output to an outlet as the result of the comparison

arguments:
  - type: list
    description: floats to compare to

methods:
  - type: args <list>
    description: replace arguments
  - type: mode <f>
    description: sets mode

flags:
  - type: -mode <f>
    description: sets mode, 0 (default) and 1 (in reverse to [moses])

draft: false
---