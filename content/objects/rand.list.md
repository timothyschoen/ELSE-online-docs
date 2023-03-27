--- 


title: rand.list

pdcategory: Random and Noise

inlets:

  1st:
  - type: bang
    description: choose an element from a given list randomly
  2nd:
  - type: list
    description: sets a new list

outlets:

  1st:
  - type: float
    description: random element from list

arguments:
  - type: list
    description: initial list

methods:
  - type: set <list>
    description: sets a new list
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal

flags:
  - type: -seed <float>
    description: sets seed

draft: false
---