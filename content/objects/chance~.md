--- 


title: chance~

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: signal
    description: impulse input

outlets:

  1st:
  - type: signal
    description: impulse according to a chance

arguments:
  - type: list
    description: list of probabilities

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: seed value (default=unique internal)

draft: false
---