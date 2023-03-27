--- 


title: chance

pdcategory: Triggers and Clocks

inlets:

  1st:
  - type: bang
    description: a bang to be passed or not
  - type: list
    description: updates arguments if more than 1 is given
  2nd:
  - type: float
    description: sets chance number if only one argument

outlets:

  1st:
  - type: bang
    description: bangs according to chance

arguments:
  - type: list
    description: list of probabilities

methods:
  - type: seed <float>
    description: a float sets seed, no float sets a unique internal



draft: false
---