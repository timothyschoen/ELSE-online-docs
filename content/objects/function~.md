--- 


title: function~

pdcategory: Signal Math

inlets:

  1st:
  - type: float/signal
    description: values from 0 to 1 reads function
  - type: list
    description: 3 or more floats set function

outlets:

  1st:
  - type: signal
    description: function output

arguments:
  - type: list
    description: 3 or more floats to set the function

methods:
  - type: exp <list>
    description: sets function with an extra exponential element for each segment
  - type: expl <list>
    description: sets exponential values for each line segment
  - type: expi <f, f>
    description: sets an exponential for a line segment specified by the first float indexed from 0

flags:
  - type: -exp <list>
    description: sets function with an extra exponential element for each segment

draft: false
---